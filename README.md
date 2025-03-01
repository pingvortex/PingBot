# PingVortex Bot API 🤖

Welcome to the **PingVortex Bot API**! This is a simple yet fun API that allows you to interact with a bot powered by basic `elif` logic. Whether you're building a chatbot, testing integrations, or just having fun, this API is here to help! 🚀

---

## API Endpoint 🌐

The API endpoint is available at:

```
https://pingvortex1.pythonanywhere.com/api/chat
```

### How to Use the API 🛠️

1. **Send a POST Request**:
   - The API accepts `POST` requests with a JSON payload containing the `content` field.
   - Example request body:
     ```json
     {
       "content": "Hello, bot!"
     }
     ```

2. **Receive a Response**:
   - The API will respond with a JSON object containing the bot's reply.
   - Example response:
     ```json
     {
       "reply": "Hello, human!"
     }
     ```

3. **Example Code (Python)**:
   ```python
   import requests

   url = "https://pingvortex1.pythonanywhere.com/api/chat"
   payload = {
       "content": "How are you?"
   }

   response = requests.post(url, json=payload)
   print(response.json())
   ```

---

## Chat with the Bot 💬

You can interact with the bot directly on the demo page:  
👉 [https://pingvortex.github.io/PingVortexBot/](https://pingvortex.github.io/PingVortexBot/)

### How It Works:
- The demo page uses the **PingVortex Bot API** to send user input and display the bot's response.
- It’s a simple example of how you can integrate the API into a web interface.

### Usage Notes:
- The `index.html` file used in the demo is **not open for direct copying**.  
- You are welcome to **remix** the code or use it **privately**, but if you want to host it publicly, please use the demo page provided above or seek permission.

---

## About the Bot 🧠

This bot is built using basic `elif` logic, making it simple and easy to understand. While it may not be the most advanced AI, it’s perfect for learning, testing, and having fun! 🎉

---

## Join the Community 🎉

Have questions, suggestions, or just want to hang out? Join my Discord server!

[![Join Discord](https://img.shields.io/badge/Join%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Efe5ws6jcP)

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by **PingVortex**
