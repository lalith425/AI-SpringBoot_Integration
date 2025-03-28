# 📬 AI Email Assistant — Spring AI + Chrome Extension

An intelligent email assistant built with **Spring AI** that auto-generates professional email responses based on your inbox context. This backend service is integrated with a **Chrome extension**, allowing users to generate, preview, and send AI-powered replies directly from their email interface.

🚀 Features

- ✨ Auto-generate email responses using Spring AI (OpenAI-compatible)
- 🧠 NLP-powered context awareness for better replies
- 🧩 Chrome extension for seamless Gmail/Outlook integration
- ⚙️ REST API built with Java + Spring Boot
- 📦 Lightweight and easy to deploy





---

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot + Spring AI**
- **OpenAI / HuggingFace integration**
- **Chrome Extension (HTML, JS)**
- **REST API**
- **Maven**

---

## 🧪 Setup Instructions

### 1. Backend (Spring Boot + Spring AI)

```bash
# Clone the repo
git clone https://github.com/yourusername/ai-email-assistant.git
cd ai-email-assistant/backend

# Set your OpenAI or other API key in application.properties
vim src/main/resources/application.properties

# Run the application
./mvnw spring-boot:run
