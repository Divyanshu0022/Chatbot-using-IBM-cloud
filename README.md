## 🚀 Watsonx Assistant Chatbot Setup Guide
<img width="1920" height="1080" alt="Screenshot (333)" src="https://github.com/user-attachments/assets/d7ef7e9d-5579-4d00-a2cf-9343afb4b966" />
<img width="1920" height="1080" alt="Screenshot (338)" src="https://github.com/user-attachments/assets/ddbbd4d1-422c-415b-9105-2b46fd728541" />
<img width="1920" height="1080" alt="Screenshot (341)" src="https://github.com/user-attachments/assets/490c0ff0-7ef7-41c7-b788-d50594f86e19" />
<img width="1920" height="1080" alt="Screenshot (344)" src="https://github.com/user-attachments/assets/d8126381-5c4b-444f-bf52-e5527195519d" />

This repository documents the creation and deployment of a multi-domain chatbot using **Watsonx Assistant**, tailored for dynamic website integration. The setup enables contextual activation of distinct bots (e.g., admission, placement) based on keyword triggers.

### 🔧 Steps to Build and Customize Your Chatbot

1. **Resource Cleanup**
   - Ensure any conflicting services or assistant resources are removed or reset to prevent deployment issues.

2. **Launch Assistant Services**
   - From the IBM watsonx console, select and launch the **Watsonx Assistant** service.
   - Assign a suitable name and resource group to organize deployments.

3. **Customize Chatbot Appearance**
   - Choose the bot's **display name, avatar, color theme**, and **branding settings** to align with your website's look.
   - Optional: Set language preferences and response tone.

4. **Create & Configure Intent Actions**
   - Define domain-specific **keywords** to route user queries (e.g., “admission”, “placement”, “enrollment”, “study”).
   - This helps the assistant activate the correct dialogue flow among multiple bots.

5. **Set Initial Conversation Parameters**
   - Decide what the assistant should say first (e.g., “Hi, how can I assist you today?”).
   - Choose **data types**, expected **user input**, and bot-driven **follow-up questions**.
   - Preview the flow live to validate responses and interaction logic.

6. **Keyword-Driven Bot Activation**
   - Test by entering greetings like “hiee” (no valid keyword) to see fallback behavior.
   - Inputting defined keywords like “admission” or “placement” will trigger the appropriate bot domain.

7. **Domain-Specific Setup**
   - For each domain (e.g., **Placement**), create a new flow.
   - Populate it with **user options**, **queries**, and corresponding assistant responses.
   - Use buttons, lists, or dropdowns for guided navigation if needed.

8. **Integration, Analysis & Publishing**
   - Integrate the assistant into your website via embed code or API.
   - Analyze user interactions with built-in dashboards.
   - Publish your chatbot in a few clicks and test real-time interactions.

