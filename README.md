✨ An **Intelligent AI ChatBot** 

that provides helpful responses to user queries on a wide range of topics within their Zoom conversation discussions by using Cerebras' advanced language models on the Zoom Developers’ platform.😊

## Core Features:

Real-Time Responses: Engages with messages in Zoom Team Chat, offering instant replies.
Contextual Awareness: Keeps track of conversation history to provide context-aware responses.
Versatile Use: Operates in direct messages or within group chats and channels.
Speed and Precision: Delivers information and assists with tasks efficiently and accurately.
Through this project, I’ve also had the chance to experience firsthand how AI can be a supportive companion. More on that below!

## Architecture:


![image](https://github.com/user-attachments/assets/e6f02d29-09f2-4af4-b86d-0e423e084716)


Without wasting time on introduction, let’s go straight to the practical part.
So, Shall we start?

### 1.  Let’s Download or update Zoom, If you haven’t:

![Screenshot 2024-12-08 at 4 34 31 PM (2)](https://github.com/user-attachments/assets/de1cbbde-d5c4-4cc8-b475-d8cdf8a45b8d)



### 2. Steps to download Ngrok:
    
   * Installation: For [MacOS](https://ngrok.com/docs/getting-started/?os=macos)
   * Sign up for an [ngrok](https://dashboard.ngrok.com/get-started/setup/macos) account.
   * Copy your [ngrok authtoken](https://dashboard.ngrok.com/get-started/your-authtoken) from your ngrok dashboard.

Run the following command in your terminal:      
```
ngrok config add-authtoken <TOKEN>
```
Expose your tunnel:   

```
ngrok http http://localhost:4000
```

### 3. Moving onto the [Zoom Developer Platform:](https://developers.zoom.us/)

### **Create a Team Chat App:**

* Create an account on the zoom, Login to Zoom Marketplace. And Assign a name to the Bot.


* Click on Build App.

* In the surface section, Select where to use that app.

   <img width="792" alt="Screenshot 2024-11-16 at 2 06 25 AM" src="https://github.com/user-attachments/assets/efbcb426-0215-4a7a-a6be-d64caf5ad4fb">

* Enable Team Chat Subscription.

   <img width="729" alt="Screenshot 2024-11-16 at 2 08 55 AM" src="https://github.com/user-attachments/assets/01f43764-d5ce-44cd-8817-5c9ddaaea0a5">

* On the Local Test page, add and preview your app and share it with internal users.

   <img width="781" alt="Screenshot 2024-11-16 at 2 10 30 AM" src="https://github.com/user-attachments/assets/cb712d28-b027-483b-97e5-674971193b4b">


### 4. Setting up a webhook receiver:

   * refer //server.js file.
   * To use this: First install node.
     
  If you do not have node installed, install it first:

   ```
   brew install node@22
   ```

  
  Install Expree:
  ```
  npm install express
  ```


  Run the server:
  ```
  node server.js
  ```


### 5. Create a new file .env:

   ```
   ZOOM_CLIENT_ID=your_zoom_client_id
   ZOOM_CLIENT_SECRET=your_zoom_client_secret
   ZOOM_BOT_JID=your_zoom_bot_jid
   CEREBRAS_API_KEY=your_cerebras_api_key
   ```

### 6. Send ChatBot Message:

   * Refer //sendMessage.js file.
   * Generating an Access token (refer token.js)


### 7. Let's move on [Cerebras:](https://inference-docs.cerebras.ai/quickstart)

   * Install the Cerebras Inference library
     ```
     npm install @cerebras/cerebras_cloud_sdk
     ```

   * Create Cerebras file

     refer //cerebras.js file.

### 8. What’s Next?

The Conversational ChatBot is ready to enhance Zoom Team Chats with intelligent interactions!

See it in action:

Your AI chatbot responding in Zoom (consider replacing this image with an updated screenshot that demonstrates the chatbot’s capabilities.)
  

  <img width="714" alt="Screenshot 2024-11-16 at 2 12 41 AM" src="https://github.com/user-attachments/assets/003bfbb0-f72f-4b8e-ab09-902675bcac3b">


-It should look like:


  <img width="312" alt="Screenshot 2024-11-16 at 2 13 21 AM" src="https://github.com/user-attachments/assets/5b96dd0d-e4df-4c44-bd83-45e42b83753a">




<img width="1440" alt="Screenshot 2024-12-08 at 4 24 28 PM" src="https://github.com/user-attachments/assets/3bade701-4ab6-4d62-9179-7b75edef0e86">



That was my experience with AI tools. I would love to know your story with AI...


## References:

* [Documents](https://developers.zoom.us/docs/team-chat-apps/create/)
* [Cerebras](https://inference-docs.cerebras.ai/quickstart)

## 💬 Feedback & Support

I'm always looking to improve! Share your thoughts and suggestions:

- **Email:** y_mahendran@u.pacific.edu
- **GitHub:** [YogeshMahendran](https://github.com/aran-yogesh)
- **Linkedin:** [YogeshMahendran](https://www.linkedin.com/in/aran-yogesh/)


## 📢 Contributing

Would you be interested in contributing? I welcome your improvements and ideas. You can Fork the repository, make changes, and submit a pull request!


<a href="https://www.linkedin.com/in/aran-yogesh/"> ![LinkedIn Profile](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white) </a>











