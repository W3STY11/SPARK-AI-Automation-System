`// Replace these with your webhook URLs`  
`const WEBHOOK_URL_NEWSLETTER_C = "webhook scenario 3 CONTENT FORMATTER";`  
`const WEBHOOK_URL_NEWSLETTER_E = "webhook scenario 4 FINAL SENDER";`  
`const WEBHOOK_URL_FILTERED_G = "webhook scenario 2 CONTENT AGGREGATOR";`  
`const WEBHOOK_URL_FILTERED_E = "webhook scenario 7 AI TOOLS PROCESSOR";`  
`const WEBHOOK_URL_FILTERED_F2 = "webhook scenario 6 SERRALA DAILY INSIGHTS PROCESSOR";`  
`const WEBHOOK_URL_FILTERED_F = "webhook scenario 8 UPCOMING EVENTS";`

`function onEditTrigger(e) {`  
 `if (!e) return; // Prevent error if function is run manually without the event object`

 `const sheet = e.range.getSheet();`  
 `const sheetName = sheet.getName();`  
 `const editedValue = e.value; // after edit`

 `// Only act if value is exactly "Yes"`  
 `if (editedValue !== "Yes") return;`

 `// "Newsletter Drafts" Column C`  
 `if (sheetName === "Newsletter Drafts" && e.range.columnStart === 3) {`  
   `sendWebhook(WEBHOOK_URL_NEWSLETTER_C, {`  
     `sheet: sheetName,`  
     `column: "C",`  
     `value: editedValue,`  
     `row: e.range.rowStart`  
   `});`  
 `}`  
 `// "Newsletter Drafts" Column E`  
 `else if (sheetName === "Newsletter Drafts" && e.range.columnStart === 5) {`  
   `sendWebhook(WEBHOOK_URL_NEWSLETTER_E, {`  
     `sheet: sheetName,`  
     `column: "E",`  
     `value: editedValue,`  
     `row: e.range.rowStart`  
   `});`  
 `}`  
 `// "Filtered Articles" Column H`  
 `else if (sheetName === "Social Media Posts" && e.range.columnStart === 7) {`  
   `sendWebhook(WEBHOOK_URL_FILTERED_G, {`  
     `sheet: sheetName,`  
     `column: "G",`  
     `value: editedValue,`  
     `row: e.range.rowStart`  
   `});`  
 `}`  
 `// "AI Tools And Updates" Column E`  
 `else if (sheetName === "AI Tools And Updates" && e.range.columnStart === 5) {`  
   `sendWebhook(WEBHOOK_URL_FILTERED_E, {`  
     `sheet: sheetName,`  
     `column: "E",`  
     `value: editedValue,`  
     `row: e.range.rowStart`  
   `});`  
 `}`  
  `// "STS Blog Posts" Column F2`  
 `else if (sheetName === "STS Blog Posts" && e.range.columnStart === 6) {`  
   `sendWebhook(WEBHOOK_URL_FILTERED_F2, {`  
     `sheet: sheetName,`  
     `column: "F",`  
     `value: editedValue,`  
     `row: e.range.rowStart`  
   `});`  
 `}`  
  `// "Upcoming Events" Column F`  
 `else if (sheetName === "Upcoming Events" && e.range.columnStart === 6) {`  
   `sendWebhook(WEBHOOK_URL_FILTERED_F, {`  
     `sheet: sheetName,`  
     `column: "F",`  
     `value: editedValue,`  
     `row: e.range.rowStart`  
   `});`  
 `}`  
`}`

`function sendWebhook(url, payload) {`  
 `var options = {`  
   `"method": "post",`  
   `"contentType": "application/json",`  
   `"payload": JSON.stringify(payload)`  
 `};`  
 `try {`  
   `UrlFetchApp.fetch(url, options);`  
 `} catch (err) {`  
   `Logger.log("Webhook failed: " + err);`  
 `}`  
`}`  
