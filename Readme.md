# 📧 n8n Email Automation

An automated email sending workflow built using **n8n** and **Google Sheets**. This workflow reads recipient data from a Google Sheet, processes each row, sends personalized emails through Gmail, and updates the sheet with the delivery status.

---

## 🚀 Features

- Read recipient data from Google Sheets
- Process records one by one using Loop Over Items
- Customize email fields
- Read attachments from local disk
- Send emails using Gmail
- Update email status in Google Sheets
- Prevent duplicate processing by tracking status

---

## 🛠️ Tech Stack

- n8n
- Gmail API
- Google Sheets API
- JavaScript
- Local File System

---

## 📂 Workflow Structure

```

Manual Trigger
│
├── Read Rows (Google Sheets)
│
├── Loop Over Items
│
├── Edit Fields
│
├── Read File From Disk
│
├── JavaScript Code
│
├── Gmail
│
└── Update Row in Google Sheets

```

---

## 📁 Repository Structure

```

My-n8n-projects/
│
├── Work-flows/
│   └── Email Automation.json
│
├── README.md
└── .gitignore

```

---

## ⚙️ Prerequisites

Before importing the workflow, configure:

- Google Sheets Credentials
- Gmail Credentials
- File path for attachments
- Sheet ID
- Gmail account

---

## 📥 Import Workflow

1. Clone this repository

```bash
git clone https://github.com/Harikrishnang-cloud/My-n8n-projects.git
```

2. Open n8n

3. Click **Import Workflow**

4. Select

```

Work-flows/Email Automation.json

```

5. Configure credentials

6. Execute the workflow

---

## 📊 Workflow Overview

1. Read recipient details from Google Sheets.
2. Loop through each row.
3. Prepare email data.
4. Attach files if required.
5. Send email using Gmail.
6. Update the status in Google Sheets.

---

## 📌 Future Improvements

- AI-powered email personalization
- Automatic follow-up emails
- Retry failed emails
- Email scheduling
- Logging & analytics
- Duplicate email detection
- Multi-template support

---

## 👨‍💻 Author

**Harikrishnan G**

- GitHub: https://github.com/Harikrishnang-cloud
- LinkedIn: https://www.linkedin.com/in/harikrishnan-g

---

## 📜 License

This project is licensed under the MIT License.