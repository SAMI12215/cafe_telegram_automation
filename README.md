# cafe_telegram_automation
☕ Telegram Cafe Automation Bot (Make.com Scenario)

📌 Project Overview

This project is an automated cafe ordering system built with Make.com and Telegram Bot.
The bot receives customer messages, parses the order, sends automatic replies, and routes orders based on the selected drink.

---

⚙️ How It Works

The scenario flow inside Make.com:

1. Telegram Bot – Watch Updates
   Receives incoming messages from customers.

2. Greeting Filter
   If the user sends:
   
   hello / hi / مرحبا
   
   The bot replies automatically:
   
   Welcome! What is your order?

3. Text Parser
   Parses the order using this format:
   
   name - drink - size
   
   Example:
   
   Ali - Latte - Large

4. Tools – Set Variables
   Stores parsed values into variables:
   
   - name
   - drink
   - size

5. Router
   Routes orders depending on the drink type (Latte, Espresso, Cappuccino, etc.).

6. Telegram Bot – Send Message
   Sends confirmation messages or forwards orders.

---

💬 Example Input

Ali - Latte - Large

Output

- Name: Ali
- Drink: Latte
- Size: Large

---

🚀 Features

- Automatic greeting reply
- Smart order parsing
- Dynamic routing with filters
- Automated Telegram responses
- Easy to extend with Gmail or Google Sheets

---

🧩 Tools Used

- Make.com
- Telegram Bot API
- Text Parser Module
- Router Module
- Tools (Set Variables)

---

🛠️ Setup Instructions

1. Import the Blueprint into Make.com.
2. Connect your Telegram Bot using Bot Token.
3. Click Run once to test.
4. Send a message to the bot using the order format.

---

📎 Notes

- Order format must be:

name - drink - size

- Filters can be customized for any drink type.

---

👨‍💻 Purpose

This project demonstrates how to build a simple automation workflow for cafe order management using Telegram and Make.com.

---

⭐ Feel free to modify and improve the scenario!
