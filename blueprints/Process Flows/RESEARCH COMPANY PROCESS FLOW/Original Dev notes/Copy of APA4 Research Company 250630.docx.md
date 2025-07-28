  
**Agentic Process Automation \#4 (APA4 – Research Company)**

**Research Company – Non-Microsoft Environment**

**Purpose**

Automate executive-level company research for sales, marketing, or strategic analysis using low-code/no-code tools, ChatGPT, and readily available public APIs outside the Microsoft stack.

---

**Step-by-Step Process Flow**

**1\. Trigger**

* **Manual:** User enters company name in google sheet, which will trigger the APA.

**2\. Extract Request Details**

* Make scenario extracts company name.

**3\. Retrieve Prompting Supplement**

* Make retrieves a “prompting supplement” document from Google Drive that defines the structure, style, and required research sections for ChatGPT (e.g., revenue, growth, ERP system, business segments, treasury pain points, etc.).

**4\. AI Company Research via ChatGPT**

* Make sends the company name and the prompting supplement to ChatGPT.  
* **Prompt:** “Research \[Company Name\] and draft a structured executive summary according to the sections below…”  
  * *Sections typically include*:  
    * Overview (50 words)  
    * Revenue, profitability, and growth (last 2–3 years)  
    * Key products/services  
    * Lines of business  
    * Countries of operation  
    * Currencies used  
    * Banking relationships  
    * Treasury operations (centers, cash management, tech stack)  
    * Primary ERP system  
    * Corporate structure/affiliates  
    * Key sales insights (50-word summary of treasury/finance pain points/opportunities)  
    * Include a link to and summary of the 5 most recent articles mentioning the company regarding changes in organizational structure, M\&A activity, technological stack changes, or critical Financial information.

**6\. Visuals/Logos**

* Use an OpenGraph or scraping module to retrieve company logo or relevant images, if needed for presentation.

**7\. Report Generation**

* Use cheaper AI model to ensure consistent formatting of the output report  
* Make compiles the AI-generated executive summary into a formatted Google Doc (or Google Sheet row).  
* Document is titled “\[Company Name\] Executive Summary – YYMMDD”.  
* **Cloud Storage:** Saved in a “Company Research” folder on Google Drive.

**8\. Logging & Tracking**

* Key summary data (company name, Doc URL, date, process trigger flag, process status, tracking number – unique identifer) logged to a master Google Sheet for history reporting/search.  
* Sequential tracking number assigned.

**9\. Delivery**

* Create email with google doc attachment and deliver to defined list of email accounts.  
* PDF or Doc link sent to requester via Gmail (with option to share with others).

**10\. Archiving & Feedback**

* All research docs archived in Google Drive.  
* Optional feedback link for user to submit corrections or additional research requests.

---

**Key Data Fields (Google Sheet)**

* Request Date / Research Date  
* Company Name  
* Sequential Research ID  
* Revenue (latest available)  
* Growth Rate / Profitability  
* ERP System  
* Country(ies) of Operation  
* Business Segments  
* Treasury Ops Notes  
* Doc Link  
* Requester / Editor  
* Status (Complete/Pending)  
* (Optional) Company Logo/Image URL

---

**Optional/Future Enhancements**

* Add Salesforce or Salesloft integration for client/contact matching  
* Option to trigger process from MS Teams or other chatbot  
* Automated archiving in additional formats (PDF, HTML)

---

**Research Company – Microsoft Environment**

**Purpose**

Automate, enrich, and document company research for sales/strategy using Microsoft-native tools (Power Automate, Teams, SharePoint, Copilot Studio), integrating proprietary/internal systems (Salesforce, Salesloft, ZoomInfo) alongside AI-generated insights.

---

**Step-by-Step Process Flow**

**1\. Trigger**

* **Teams:** User enters request via Teams message (“Research Company: \[Company Name\]”)  
* **Alternate:** Outlook email, Power App form, or SharePoint form

**2\. Extract Request Details**

* Power Automate parses input for company name and any additional parameters.

**3\. Retrieve Prompting Supplement**

* Power Automate retrieves a “prompting supplement” doc from SharePoint (defines structure, tone, and target insights for Copilot/ChatGPT).

**4\. AI Company Research via Copilot/ChatGPT**

* Power Automate (or Copilot Studio agent) sends the company name and supplement prompt to ChatGPT (via OpenAI connector) or to Copilot Studio for LLM-based generation.  
* **Prompt:** Same structured executive summary as above, but can be enriched for enterprise use, including compliance language or additional context.

**5\. Proprietary Data Enrichment**

* Power Automate queries Salesforce/Salesloft for:  
  * Existing accounts/contacts  
  * Most recent engagement  
  * Account owner  
  * Open/closed opportunities  
* Optionally, query ZoomInfo for technology stack, company size, leadership contacts, etc.

**6\. Visuals/Branding**

* Power Automate fetches company logo or primary image (using OpenGraph, Bing Image Search, or internal asset bank).

**7\. Report Generation**

* Compile all AI and proprietary data into a formatted Word document (using Office Scripts or Word API).  
* Title: “\[Company Name\] Executive Summary – YYMMDD”  
* Save to SharePoint “Company Research” library.

**8\. Google/Excel Sheet Logging**

* Log summary data to a SharePoint List or Excel Online sheet:  
  * Company name  
  * Revenue, growth, profitability  
  * ERP system  
  * Business segments, countries  
  * Salesforce engagement/contact owner  
  * Doc link  
  * Editor/Requester  
  * Status

**9\. Delivery**

* Notify user via Teams (message with Doc link), Outlook email, or assign as a task in Planner/To Do.  
* Optionally, post to internal Teams channel for visibility.

**10\. Analytics & Feedback**

* Log usage and feedback in SharePoint/Excel (who requested, when, engagement).  
* Optionally, add feedback button (Power Apps) for corrections, enhancements.

**11\. Archiving**

* All research docs archived in SharePoint with versioning for audit/compliance.  
* Optional backup to OneDrive.

---

**Key Data Fields (SharePoint List/Excel)**

* Research Date  
* Company Name  
* Research ID  
* Revenue, Growth, Profitability  
* ERP System  
* Countries / Segments  
* Key Contacts (from Salesforce/Salesloft)  
* Tech Stack (from ZoomInfo)  
* Status  
* Editor/Requester  
* Link to Doc (Word/SharePoint)  
* Teams/Planner Link (if assigned)  
* Feedback (if submitted)

---

**Optional/Future Enhancements**

* Power Automate approval workflow for QC before delivery  
* Scheduled re-research/reminders  
* Integration with Microsoft Syntex for document tagging/classification  
* Automated translation/localization for global teams

---

**Comparative Notes**

* **Non-Microsoft:** Fastest to implement, leverages Make/Zapier, Google tools, and direct AI, best for proof-of-concept, smaller teams, or pre-enterprise use.  
* **Microsoft:** Scalable, secure, integrates internal data (Salesforce, ZoomInfo), leverages SharePoint/Teams for access control and compliance, better for mature/regulated orgs.

