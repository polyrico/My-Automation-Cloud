## 💬 Whatsapp text and voice chat
This flow was created with the instruction of [Programing Pills](https://www.youtube.com/watch?v=p3gz4pFxL4U&t) and [Polyrico Dev](https://github.com/polyrico)

### 🎯 Key Points
#### 📝 1. Gemini API and Transcript service
* For use Gemini API you have to create a token in [here](https://ai.google.dev/gemini-api/docs) for the Gemini APIs (Don't worry, it's still free but it depends on the model you use)
* For the audio recognition use Gemini Transacipt to text with the same API, it isn't neccesary create another token or pay something additional.
#### 🤖 2. Whatsapp Comunication
* The recive the messages from Whatsapp is neccesary use [Evolution API v2](https://doc.evolution-api.com/v1/pt/get-started/introduction), and configure your own Whatsapp account into Evolution, later configure the Webhook
* To send the messages you have to configure the endpoint to [Evolution API Send Plain Text](https://doc.evolution-api.com/v1/api-reference/message-controller/send-text#send-plain-text)
#### 🗃️ 4. Postgres to persist the conversations (optional)
* In the [My Automation Cloud](https://github.com/polyrico/My-Automation-Cloud) you going to find the PostgreSQL service and your credentials to configure it in the flow.

##### 🗒️ NOTE 
This point is optional, and you can use the flow without a memory or with the Simple Storage provided for n8n.