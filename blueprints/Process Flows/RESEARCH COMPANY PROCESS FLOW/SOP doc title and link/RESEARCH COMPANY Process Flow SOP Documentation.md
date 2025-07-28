**RESEARCH COMPANY PROCESS FLOW SOP DOCUMENTATION**

**Summary Overview of the System**

This system creates company reports using data from Google Sheets and daily job post scraping. Users can type a company name in the sheet and check a box to start research. Every morning, Apify scrapes Indeed for SAP-related job posts and filters out duplicates. If a new company is found, the system makes a job report. Whether started manually or from a scrape, the system uses Perplexity and ChatGPT to gather data, build a complete Company Report, and add the link back to the sheet. If an email is listed, it sends the report there too.

---

**Important Notes:**

* This automation is using GoogleApps script in the Google sheet to trigger the webhooks in make.com. The Apps script code is in a different document.

---

**Tech Stack:**

* Make.com \- automations platform  
* Google Sheet \- database and front-end UI  
* Inoreader RSS Feed \- for daily updated news articles  
* Google Workspace \- for creation and storing of files, email notifications  
* Perplexity \- for researching  
* ChatGPT \- for parsing and formatting  
* Apify \- for scraping job posts

---

**How it Works: End-to-End Flow (Front-End)**

* Note: Another system is scraping job posts in Indeed everyday to find Companies that are hiring for relevant jobs (SAP Finance, SAP Treasury, etc). This is auto-populating the google sheet database with complete Company Reports.  
* 1st step: If the user wants to manually create a company report, put the company name you want to research in the google sheets column A.  
* 2nd step: Click the checkmark in column C (start research?).  
* 3rd step: (Optional) Add another email in column B if the user wants to send the company report to another person.  
* 5th step: Wait for the complete company report as a google doc in column D.

---

**Make.com Automations Step By Step Process (Back-End)**  


1.) **RESEARCH COMPANY SYSTEM**:

* 1st step: Triggers when the checkmark is populated in google sheets column C.  
* 2nd step: Search the relevant info in google sheets.  
* 3rd step: Get the prompt from an external google document to feed to Perplexity.  
* 4th step: Perplexity researches the company and creates a report.  
* 5th step: ChatGPT searches for the main website of the company..  
* 6th step: ChatGPT formats the content as HTML to create the right structure for google docs.  
* 7th step: If the company has a job report, the text from it will be extracted to be added to the complete company report.  
* 8th step: Send a notification to the user that the company report is ready via Gmail.  
* 9th step: Set a unique tracking id variable.  
* 10th step: Add all data in the google sheet together with the company report google doc link.  
* 11th step: If there is a custom email in column B, the report will be sent to that person via gmail.  
  


2.) **JOB POST SCRAPE SYSTEM**:

* 1st step: Triggers daily at 8am and Apify scrapes Indeed for Companies that have a relevant job post (SAP Finance, SAP Treasury, etc).  
* 2nd step: Get all the data that was scraped.  
* 3rd step: Filters if the job post contains SAP on it.  
* 4th step: Filters if the company is already in the google sheets.  
* 5th step: ChatGPT creates the Job Posting Document based on the data scraped.  
* 6th step: ChatGPT formats the text result into HTML to structure for google doc.  
* 7th step: Create the Job Posting Document.  
* 8th step: Delay 5 secs to wait for the document to process.  
* 9th step: Get the google drive share link of the document.  
* 10th step: Add all data in googlesheets column E together with the link of the document.  
* 11th step: Delay 10 secs to wait for data to be processed in google sheet  
* 12th step: Trigger the “Research Company System” automation to process the complete Company Report together with the Job Posting Report for this particular company.  
* Apify Input JSON Code in the Apify make.com module/node:  
  {  
      "country": "us",  
      "maxRows": 50,  
      "maxRowsPerUrl": 20,  
      "urls": \[  
          "https://www.indeed.com/jobs?q=SAP+finance", "https://www.indeed.com/jobs?q=SAP+treasury", "https://www.indeed.com/jobs?q=SAP+cash+management"  
      \]  
  }  
  