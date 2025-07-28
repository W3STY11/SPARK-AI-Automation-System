`function onEdit(e) {`  
 `const sheet = e.source.getActiveSheet();`  
 `const editedRange = e.range;`  
 `const editedValue = e.value;`

 `// Define settings per sheet`  
 `const sheetConfigs = {`  
   `"Trigger": {`  
     `checkboxColumn: 6, // Column F`  
     `webhookUrl: "PUT WEBHOOK OF CONTENT SYSTEM 1 HERE"`  
   `},`  
   `"Blog Tracker": {`  
     `checkboxColumn: 7, // Column G`  
     `webhookUrl: "PUT WEBHOOK OF CONTENT SYSTEM 3 HERE"`  
   `}`  
 `};`

 `const sheetName = sheet.getName();`

 `// Proceed only if the sheet is in the config`  
 `if (sheetConfigs.hasOwnProperty(sheetName)) {`  
   `const config = sheetConfigs[sheetName];`

   `if (`  
     `editedRange.getColumn() === config.checkboxColumn &&`  
     `editedValue === "TRUE"`  
   `) {`  
     `const row = editedRange.getRow();`  
     `const rowData = sheet.getRange(row, 1, 1, sheet.getLastColumn()).getValues()[0];`

     `const payload = {`  
       `sheetName: sheetName,`  
       `rowNumber: row,`  
       `values: rowData`  
     `};`

     `const options = {`  
       `method: "post",`  
       `contentType: "application/json",`  
       `payload: JSON.stringify(payload)`  
     `};`

     `UrlFetchApp.fetch(config.webhookUrl, options);`  
   `}`  
 `}`  
`}`