**LINKEDIN CONTENT SYSTEM BUILD**

**Workflow \#2:  News-to-LinkedIn Blog Flow**  
Rectangle

* **Trigger**  
* **Initiated via:** Browser bookmark or webhook (built using Make’s HTTP module)  
* **Displays:** HTML form with:  
  * 3 default prompt options:  
    * “AI and finance impact”  
    * “Finance transformation in global 500 companies”  
    * “Leadership in treasury technology”  
  * Text field for custom prompt input  
  * Selection: User can choose 1, 2, or all 3 prompts

Rectangle

* **Article Search (via Perplexity API)**  
* **Request sent:** Selected prompt(s) are sent to Perplexity for broad topical search (no RSS feed required)  
* **Search logic:**  
  * **1 prompt selected:** Return 10 articles  
  * **2–3 prompts selected:** Return 5 articles per prompt (maximum of 15\)  
* **Returned fields per article:**  
  * Full text  
  * Title  
  * Publication date  
  * URL  
  * 30-word summary

Rectangle

* **Article Selection Interface**  
* **HTML page generated in Make:**  
  * Displays article **title**, **date**, **summary**, and **clickable URL**  
  * User selects one or more articles via checkboxes or buttons  
  * **No editing** of article content at this stage

Rectangle

* **Blog Post Generation (via Claude 4 Opus)**  
* **For each selected article:**  
  * Send the following to Claude 4 Opus (Anthropic API; model ID: claude-4-opus-2025 or latest):  
    * Full article text  
    * Article URL  
    * User’s writing persona  
    * User’s professional history  
    * LinkedIn posting strategy  
  * Output: A tailored LinkedIn-style blog post for each article

Rectangle

* **Delivery and Tracking**  
* **Google Drive:**  
  * Create a **Google Doc** for each blog post  
  * Save to the **“Draft”** folder  
* **Google Sheet ("Blog Tracker"):**  
  * Log:  
    * Blog post title  
    * Source article URL  
    * Google Doc link  
    * Date of creation  
    * **Status:** “Draft”  
* **User actions:**  
  * Review/edit Docs in the “Draft” folder  
  * Update blog status in Google Sheet to: **“Ready for Processing”**

Rectangle

* **Post-Edit Processing**  
* **User triggers webhook** (Make HTTP module) to initiate final flow  
* **Make checks** Google Sheet for status: “Ready for Processing”  
  * For each:  
    * Move corresponding Doc to **“Completed”** Google Drive folder  
    * Update Sheet status to: **“Processed”**

Rectangle

* **LinkedIn Draft Creation**  
* **Draft generation:**  
  * Use LinkedIn API (or manual link generation) to create LinkedIn draft posts from each “Processed” blog  
  * Update Google Sheet status to: **“Posted”**

Rectangle

* **Notifications**  
* Send **Slack or email notification** to user with:  
  * Links to **LinkedIn draft post(s)**  
  * Links to corresponding **Completed Google Docs**  
  * Confirmation that post is ready for final approval

Rectangle

* **Freelancer Notes**  
* Use **Make’s HTTP module** for both the:  
  * Browser-based trigger form  
  * Article selection interface  
* No RSS needed; configure Perplexity to **search broadly** using prompts  
* Ensure **Google Sheet status flow** supports:  
  * “Draft”  
  * “Ready for Processing”  
  * “Processed”  
  * “Posted”

