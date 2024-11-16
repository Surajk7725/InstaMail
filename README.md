# InstaMail

A **Streamlit-based** custom email sender application using the OpenAI API for content generation and Mailjet API for email delivery. 

---

### Framework Used

This application is built using **Streamlit**, a Python-based open-source framework for creating interactive web applications. Streamlit enables rapid prototyping and seamless integration of APIs, making it ideal for building data-driven dashboards and applications with minimal code.
---

## Features

- **Dynamic Email Content**: Generate personalized email content using OpenAI GPT.
- **ESP Integration**: Use Mailjet for sending, scheduling, and tracking emails.
- **Data Handling**: Upload CSV files for recipient data.
- **Real-Time Dashboard**: Track email sending status, delivery, and analytics.

---

## Prerequisites

- **Python 3.9+**
- API keys for:
  - [OpenAI](https://platform.openai.com/signup/)
  - [Mailjet](https://www.mailjet.com/)

---


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Surajk7725/InstaMail.git
   cd InstaMail
   ```
2. Install dependencies:
     ```bash
     pip install -r requirements.txt
      ```
---

## Usage

1. Run the streamlit application:
   ```bash
   streamlit run main.py
   ```
2. Run the Flask application:
     ```bash
     python track.py
     ```
3. Allows user to connect their email account.
4. Upload a CSV file with recipient details (e.g., **Name**, **Email**, **Company**).
5. Enter an email template with placeholders (e.g.,`Hello **{{Name}}**, from **{{Company}}**.`).
6. Preview and send emails or schedule them.

---
