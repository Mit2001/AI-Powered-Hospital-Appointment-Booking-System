# 🏥 AI-Powered Hospital Appointment Booking System using n8n & OpenAI

## Overview

This project is an AI-powered **Hospital Appointment Booking System** built using **n8n**, **OpenAI Chat Model**, **AI Agent**, **JavaScript**, **Google Sheets**, and **Gmail**. It automates the entire appointment booking process by intelligently extracting patient information from a single form submission and organizing it into a structured format.

The workflow begins when a patient submits an online appointment form containing their personal details and health concerns. The submitted information is passed to an **AI Agent** connected to the **OpenAI Chat Model**, which analyzes the patient's symptoms and extracts important medical information such as the **symptoms**, **recommended department**, **priority level**, and **doctor type**.

A custom **JavaScript** node then generates a unique **Appointment ID**, ensuring every appointment has a unique reference number. The extracted AI-generated information and appointment ID are formatted using the **Edit Fields** node before being automatically stored in **Google Sheets**. Finally, the workflow sends a personalized appointment confirmation email to the patient containing all relevant appointment details.

This project demonstrates how AI can automate healthcare workflows by reducing manual effort, improving data accuracy, and providing patients with a seamless appointment booking experience.

---

## Features

- 📝 Online hospital appointment booking form
- 🤖 AI-powered symptom analysis using the OpenAI Chat Model
- 🩺 Automatically extracts patient symptoms
- 🏥 Recommends the appropriate hospital department
- 🚨 Determines appointment priority based on symptoms
- 👨‍⚕️ Identifies the suitable doctor type
- 🆔 Generates a unique Appointment ID using JavaScript
- 📊 Stores appointment records in Google Sheets
- 📧 Sends automated appointment confirmation emails
- ⚡ Fully automated workflow built with n8n

---

## Workflow

```text
Patient
   │
   ▼
Hospital Appointment Form
   │
   ▼
AI Agent
   │
   ▼
OpenAI Chat Model
   │
   ▼
Extract:
• Symptoms
• Department
• Priority
• Doctor Type
   │
   ▼
Generate Appointment ID (JavaScript)
   │
   ▼
Edit Fields
   │
   ▼
Store Appointment in Google Sheets
   │
   ▼
Send Confirmation Email
   │
   ▼
Patient Receives Appointment Details
```

---

## Tech Stack

- **n8n** – Workflow Automation
- **OpenAI Chat Model** – AI-powered symptom analysis
- **AI Agent** – Extracts structured medical information
- **JavaScript** – Generates unique Appointment IDs
- **Google Sheets API** – Appointment database
- **Gmail** – Appointment confirmation emails
- **REST APIs** – Communication between integrated services

---

## How It Works

1. A patient fills out the online hospital appointment form.
2. The submitted form data is sent to the **AI Agent**.
3. The AI Agent uses the **OpenAI Chat Model** to analyze the patient's symptoms.
4. The AI extracts:
   - Symptoms
   - Recommended Department
   - Appointment Priority
   - Suitable Doctor Type
5. A **JavaScript** node generates a unique Appointment ID.
6. The **Edit Fields** node formats the final appointment record.
7. The appointment details are automatically stored in Google Sheets.
8. A personalized appointment confirmation email is sent to the patient's registered email address.

---

## Learning Outcomes

This project demonstrates:

- Workflow automation using n8n
- AI Agent implementation
- OpenAI Chat Model integration
- AI-powered information extraction
- JavaScript automation
- Google Sheets integration
- Email automation using Gmail
- REST API communication
- End-to-end healthcare workflow automation
  
---

## License

This project is created for educational purposes and portfolio demonstration. Feel free to fork, modify, and extend the workflow to build your own AI-powered hospital appointment booking system.
