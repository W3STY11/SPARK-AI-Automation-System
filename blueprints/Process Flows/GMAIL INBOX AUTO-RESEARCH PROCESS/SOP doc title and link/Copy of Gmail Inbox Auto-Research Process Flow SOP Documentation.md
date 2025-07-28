**GMAIL INBOX AUTO-RESEARCH PROCESS FLOW SOP DOCUMENTATION**

**Summary Overview of the System**

This system monitors Gmail Inbox for emails that have the subject line “Research+”, then uses ChatGPT to extract any website links included in the message. Next, Perplexity researches the extracted link and produces a concise 30-word summary of the content. ChatGPT then extracts the article’s title and the generated summary and automatically adds it to a Google Sheets file for easy reference and tracking.

---

**Tech Stack:**

* Make.com \- automations platform  
* Gmail \- source of the link to be searched  
* Perplexity  \- for researching the article in the web  
* ChatGPT \- for parsing and formatting  
* Google Sheets \- main database

---

**How it Works: End-to-End Flow (Front-End)**

* 1st step: User sends an email to himself with a subject line “Research+”.  
* 2nd step: Wait for the Data on the Google Sheets

---

**Make.com Automations Step By Step Process (Back-End)**  


1.) **GMAIL INBOX AUTO-RESEARCH**: Trigger "Research+" Label Inbox \-\> Extract Link \-\> Research Article \-\> Put Data in GSheets

* 1st step: Triggers every 15 mins and catches emails that contain “Research+” on their subject line.  
* 2nd step: ChatGPT extracts the website link.  
* 3rd step: Perplexity researches the website link and produces a 30-word summary.  
* 4th step: ChatGPT extracts the title and summary.  
* 5th step: Put all the relevant data in the Google Sheets.