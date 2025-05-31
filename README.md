

---

# Dr. AIT College Assistant Chatbot
ChatBot Link:https://cdn.botpress.cloud/webchat/v2.5/shareable.html?configUrl=https://files.bpcontent.cloud/2025/05/31/15/20250531151857-15LYVJ3C.json
## 1. People Contributed
- **Aman Kumar Sinha**
- [1DA21IS008]  


## 2. Project Dependencies/Requirements
To successfully run this chatbot, ensure the following dependencies are installed:
- **Botpress Cloud** – (Used for chatbot creation and deployment)
- **Node.js** – (For local development and Botpress CLI usage)
- **Express.js** – (Optional, if hosting on a custom server)
- **MongoDB / Firebase** – (For storing conversation history, if applicable)
- **NLP Modules** – (Built-in NLP capabilities provided by Botpress)
- **Other Dependencies** – (*Add any additional libraries or APIs used in development*)

## 3. Project Directory Structure
Below is the recommended directory structure:

```
📂 DrAIT-Chatbot
 ├── 📂 src
 │   ├── bot-config.json   # Botpress configuration file
 │   ├── intents/          # Defined conversational intents
 │   ├── responses/        # Predefined responses for queries
 │   ├── actions/          # Custom actions for chatbot interactions
 │   ├── api/              # External API integrations
 ├── 📂 public
 │   ├── index.html        # Web interface for chatbot (if applicable)
 ├── 📂 docs
 │   ├── README.md         # Documentation file
 ├── package.json          # Dependencies and scripts
 ├── botpress.config.json  # Botpress-specific settings
 ├── .env                  # Environment variables
```

## 4. Development Steps
Here are the key steps followed during the chatbot development:
1. **Bot Creation on Botpress Cloud** – Set up the bot and configured basic settings.
2. **Intent Definition** – Created various conversational intents for handling college-related queries.
3. **Training the NLP Model** – Adjusted Botpress built-in NLP to ensure better recognition of student queries.
4. **Custom Actions Integration** – Developed actions for fetching real-time information about courses, fees, and admission.
5. **API Setup** – Integrated relevant APIs to pull college-related data dynamically.
6. **Deployment** – Published the bot on Botpress Cloud and shared the webchat link.
7. **Testing & Debugging** – Ran extensive tests to optimize responses and functionality.

---

This README file helps other developers or users understand my chatbot’s setup, structure, and functionality. Let me know if you'd like to refine or add more details! 
