# 📅 Habit Reminder Bot using n8n

An automated reminder workflow built with **n8n** that sends a personalized daily habit checklist directly to **Telegram**. This workflow demonstrates scheduled automation, message formatting, and Telegram bot integration without requiring external APIs or paid services.

Built as part of my **30-Day n8n Automation Portfolio**, this project showcases workflow automation for personal productivity and daily habit tracking.

---

## 📌 Features

- ⏰ Runs automatically on a daily schedule
- 📋 Sends a personalized habit checklist
- 📅 Displays the current date automatically
- 📲 Delivers reminders directly to Telegram
- 🆓 No external API required
- ⚡ Fully automated workflow

---

## 🛠️ Technologies Used

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

Automatically starts the workflow at a scheduled time each day.

---

### 2. Edit Fields (Set)

Creates a formatted habit reminder message using n8n expressions.

Example Output:

```text
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

🤖 Generated automatically using n8n.
```

---

### 3. Telegram

Sends the formatted habit reminder directly to your Telegram account.

---

## 📁 Repository Structure

```text
Habit-Reminder-Bot/
│
├── README.md
├── workflow.json
│
├── screenshots/
│   ├── workflow.png
│   ├── workflow-execution.png
│   └── telegram-output.png
```

---

## 📷 Screenshots

Include the following screenshots:

- Complete Workflow
- Workflow Execution
- Telegram Output

---

## 🎯 Learning Objectives

This project demonstrates:

- Scheduled Workflow Automation
- Telegram Bot Integration
- Message Formatting
- n8n Expressions
- Personal Productivity Automation
- No-Code / Low-Code Development

---

## 🚀 Future Improvements

- Store habits in Google Sheets
- Support different reminders for weekdays and weekends
- Habit completion tracking
- Multiple reminders throughout the day
- Customizable habit lists
- Google Calendar integration
- Weekly habit reports

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Belio C. Sinangote**

BS Information Technology Student  
Cebu Technological University (CTU)

**GitHub:** https://github.com/belioautomation

This project is part of my **30-Day n8n Automation Portfolio**, showcasing practical workflow automation using **n8n**, **Telegram Bot API**, and **scheduled workflows**.
