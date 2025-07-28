openapi: 3.1.0  
info:  
  title: Webhook Caller API  
  description: Sends a message to a Make.com webhook and returns the response.  
  version: 1.0.1  
servers:  
  \- url: https://hook.eu2.make.com  
    description: Make.com Webhook Server  
paths:  
  /q2s9f9x4x7a5765i3dwlqi0hf10ouj7n:  
    post:  
      operationId: sendMessageToWebhook  
      summary: Send a message to the webhook and receive the response.  
      requestBody:  
        required: true  
        content:  
          application/json:  
            schema:  
              type: object  
              properties:  
                message:  
                  type: string  
              required:  
                \- message  
      responses:  
        "200":  
          description: Webhook response  
          content:  
            application/json:  
              schema:  
                type: object  
                properties: {}  
                additionalProperties: true

