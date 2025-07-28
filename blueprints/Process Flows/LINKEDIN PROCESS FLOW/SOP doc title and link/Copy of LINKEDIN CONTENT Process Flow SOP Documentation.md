**LINKEDIN CONTENT PROCESS FLOW SOP DOCUMENTATION**

**Summary Overview of the System**

This system streamlines LinkedIn content creation using data coming from InoReader RSS feed articles. Users select a date, topic, and their name, then trigger the flow with a checkmark. The system pulls articles from Inoreader and uses ChatGPT to pick the top 3 content. Claude customizes the content using user-specific personas and creates the LinkedIn post, ChatGPT formats the posts to include unicode bolding, and creates Google Docs for review. Once approved, a final automation moves the document and posts the content directly to the user’s LinkedIn profile.

---

**Important Notes:**

* This automation is using GoogleApps script in the Google sheet to trigger the webhooks in make.com. The Apps script code is in a different document.  
* The system needs a different “Persona” Google Document for each user. The user needs to map each document ID correctly in the “Switch Name to Document ID” module/node in make.com Content System 2\.  
*  The user needs to create a different GoogleDrive Folder to store all the completed LinkedIn content and should map it in the Content System 3 google drive module/node in make.com.

---

**Tech Stack:**

* Make.com \- automations platform  
* Google Sheet \- database and front-end UI  
* Inoreader RSS Feed \- for daily updated news articles  
* Google Workspace \- for creation and storing of files  
* Claude \- for creation of content  
* ChatGPT \- for choosing top articles and parsing/formatting

---

**How it Works: End-to-End Flow (Front-End)**

* 1st step: User adds the date today in column A.  
* 2nd step: User picks (puts a checkmark on columns B/C/D) a relevant topic he wants to get data from.  
* 3rd step: User picks his/her name from column E.  
* 5th step: If everything is ready, the user puts a checkmark on column F to trigger the automation.  
* 6th step: User goes to the “Blog Tracker” sheet and waits for the new document to be added.  
* 7th step: User reviews the content in the google document (column B).  
* 8th step: If content is good, put checkmark on column G (“Ready to Post?”) to automatically post on the user’s LinkedIn Profile.

---

**Make.com Automations Step By Step Process (Back-End)**  


1.) **LINKEDIN CONTENT SYSTEM 1**: Get Articles from Inoreader \-\> ChatGPT Chooses Top 3 \-\> Send data to Googlesheets

* 1st step: Triggers when the checkmark is populated in “Trigger” sheets column F.  
* 2nd step: Search the relevant info in google sheets.  
* 3rd step: Depending on the Topic chosen, it then goes to the relevant route and get the RSS feed data from Inoreader for that particular topic.  
* 4th step: Set a unique identifier variable for that news article.  
* 5th step: Searches for a duplicate link in google sheets.  
* 6th step: Put all the articles data to the “All Articles” sheet for future reference.  
* 7th step: Aggregate all the needed data into one bundle.  
* 8th step: ChatGPT chooses top 3 articles from the aggregated data and produces a unique LinkedIn angle.  
* 10th step: Iterate the 3 articles and put all data into the “ChatGPT Filtered” sheet.  
* 11th step: Close the loop of the iteration and wait for 10 secs.  
* 12th step: Trigger the “Content System 2” Automation to process the 3 articles.  
  


2.) **LINKEDIN CONTENT SYSTEM 2**: Triggers from Content System 1 \-\> Checks Status \-\> Creates Linkedin Post \-\> Creates GoogleDoc

* 1st step: Triggers from “Content System 1” automation.  
* 2nd step: Check the relevant data in google sheets.  
* 3rd step: Switches the document ID for the google doc Persona depending on the user’s name (every user has a different persona).  
* 4th step: Get the persona from the google document.  
* 5th step: Feed the persona to Claude and create a LinkedIn post.  
* 6th step: ChatGPT formats the content to include unicode bolding of titles.  
* 8th step: Create the google document.  
* 9th step: Update “done” status in “ChatGPT Filtered” sheet.  
* 10th step: Delay 10 secs to wait for google doc to be processed.  
* 11th step: Get GoogleDrive File ID of the document for next Content System Automation.  
* 12th step: Add all the relevant data to “Blog Tracker” sheet.

3.) **LINKEDIN CONTENT SYSTEM 3**: Trigger from "Ready to post?" \-\> Move File \-\> Create LinkedIn Post

* 1st step: Triggers from “Ready to post?” (column G) sheet.  
* 2nd step: Check the relevant data in google sheets.  
* 3rd step: Move the google document file to the “Completed” GoogleDrive folder.  
* 4th step: Update the status to “processed”.  
* 5th step: Get the LinkedIn post content from the google document.  
* 6th step: Routes to different LinkedIn profiles depending on the name of the user.  
* 8th step: Post the LinkedIn content to the user's account.