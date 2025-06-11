# 🌍 Language Translation Bot (Amazon Lex + Translate + Lambda)

This project demonstrates how to build a chatbot that can translate words or sentences into another language using **Amazon Lex**, **AWS Lambda**, and **Amazon Translate**. It's a simple but powerful introduction to building intelligent conversational interfaces with real-time language processing.

---

## 🧾 Overview of Project ☁️

The goal of this project is to build a multilingual translation chatbot. Users can type a sentence or word into the chat window, and the bot will respond with a translated version using Amazon Translate.

---

## 🗺️ Architectural Diagram

Below is the architecture of the translation bot system:

![Architectural Diagram](https://github.com/Yuehan07/language-translation-bot/blob/main/Architectural%20Diagram.png)

---

## 🛠 Services Used

| AWS Service       | Purpose                                                         |
|-------------------|-----------------------------------------------------------------|
| **Amazon Lex**     | Used to create and manage the chatbot and conversation flow     |
| **AWS Lambda**     | Handles backend logic and invokes Amazon Translate API          |
| **Amazon Translate** | Provides the translation functionality                        |
| **IAM**            | Grants secure access between Lex, Lambda, and Translate         |

---


## 👩‍💻 Steps to be Performed

In this project, we go through the following key steps:

1. **Create an empty chatbot** using Amazon Lex
2. Define **Intents** and **Slots** for language input and text
3. Specify **Fulfillment** for handling logic
4. **Create an IAM Role** with permissions for Lex, Lambda, and Translate
5. **Build an AWS Lambda function** that calls Amazon Translate API
6. **Test the Lambda function** independently
7. **Test the chatbot** with different language inputs via Lex Console

---


## ✅ Final Result

Once deployed, your chatbot will allow users to input any sentence and receive the translated version instantly:

![Final Result](https://github.com/Yuehan07/language-translation-bot/blob/main/%20Final%20Result.png)

---

## 📌 Notes

- ✅ Built entirely using **serverless architecture**
- ✅ Supports multiple languages via Amazon Translate
- ✅ Can be further extended to support voice input with Amazon Polly or Amazon Connect

---

## ✨ Author

Developed by [Yuehan Chen (Olivia)](https://github.com/Yuehan07)

If you like the project, feel free to ⭐ star or fork the repository!

---

## 📄 License

This project is licensed under the MIT License.

