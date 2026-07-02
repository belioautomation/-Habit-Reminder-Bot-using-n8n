# 📅 Habit Reminder Bot using n8n

An automated workflow built with **n8n** that sends a daily habit reminder directly to **Telegram**. This project demonstrates scheduled automation, message formatting, and Telegram bot integration without requiring any external APIs or paid services.

---

## 📌 Overview

This workflow automatically performs the following tasks:

- Runs every day at a scheduled time.
- Generates a personalized habit reminder.
- Includes the current date in the message.
- Sends the reminder directly to Telegram.

---

## 🚀 Features

- ⏰ Daily scheduled execution
- 📋 Daily habit checklist
- 📲 Telegram notification
- 📅 Automatically displays the current date
- 🔑 No API key required
- 💯 Fully automated

---

## 🛠 Tech Stack

- n8n
- Schedule Trigger
- Edit Fields (Set)
- Telegram Bot API

---

## 📂 Workflow

```text
Schedule Trigger
        │
        ▼
Edit Fields (Set)
        │
        ▼
Telegram
```

---

## ⚙️ Workflow Explanation

### 1. Schedule Trigger

Automatically starts the workflow every day at the configured time.

---

### 2. Edit Fields (Set)

Creates a formatted daily habit reminder message using expressions.

Example Output:

```
📅 Daily Habit Reminder

Today's Habits

📚 Study for 1 hour

💧 Drink 8 glasses of water

🏃 Exercise for 30 minutes

📖 Read 20 pages

🧘 Meditate for 10 minutes

📅 Date:
July 02, 2026

💪 Small progress every day leads to big results.

🤖 Generated automatically with n8n.
```

---

### 3. Telegram

Sends the formatted habit reminder directly to your Telegram account.

---

## 📁 Project Structure

```
Habit-Reminder-Bot/
│
├── README.md
├── workflow.json
└── screenshots/
    ├── workflow.png
    ├── workflow-execution.png
    └── telegram-output.png
```

---

## 📸 Screenshots

Include the following screenshots:

- Workflow Editor
- Successful Workflow Execution
- Telegram Output

Example:

```
screenshots/
    workflow.png
    workflow-execution.png
    telegram-output.png
```

---

## 💡 Use Cases

- Daily study reminders
- Fitness and workout reminders
- Reading goals
- Hydration tracking
- Meditation reminders
- Personal productivity
- Portfolio automation project

---

## 🔮 Future Improvements

- Store habits in Google Sheets
- Send different reminders on weekdays and weekends
- Add habit completion tracking
- Send reminders multiple times a day
- Allow users to customize their habit list
- Integrate with Google Calendar
- Generate weekly habit reports

---

## 📚 What I Learned

This project helped me gain hands-on experience with:

- Workflow automation using n8n
- Schedule Trigger node
- Edit Fields (Set) node
- Expressions
- Telegram Bot integration
- Scheduled workflows

---

## 🏷 Skills Demonstrated

- n8n
- Workflow Automation
- Schedule Trigger
- Edit Fields (Set)
- Expressions
- Telegram Bot API
- Scheduled Automation
- No-Code / Low-Code Development

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project helpful, consider giving it a star!
