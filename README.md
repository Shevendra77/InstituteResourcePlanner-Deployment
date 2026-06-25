# 🏫 Institute Resource Planner

A complete Institute Management System for managing resources, users, and allocations.
Built with Spring Boot, MySQL, and Docker.

---

## 🚀 Run in 3 Simple Steps

### ✅ Prerequisites
- Install [Docker Desktop](https://www.docker.com/products/docker-desktop)

---

### Step 1: Download `docker-compose.yml`

👉 [Click here to download](https://raw.githubusercontent.com/Shevendra77/InstituteResourcePlanner-Deployment/main/docker-compose.yml)

Or using terminal:
```bash
curl -O https://raw.githubusercontent.com/Shevendra77/InstituteResourcePlanner-Deployment/main/docker-compose.yml
```

---

### Step 2: Fill your credentials in `docker-compose.yml`

Open the file and replace these values:

```yaml
EMAIL_USER: your_gmail@gmail.com        # Your Gmail
EMAIL_PASS: your_app_password           # Gmail App Password
TWILIO_SID: your_twilio_sid             # Twilio Account SID
TWILIO_TOKEN: your_twilio_token         # Twilio Auth Token
TWILIO_PHONE: your_twilio_phone         # Twilio Phone Number
```

> 💡 Gmail App Password banane ke liye: Google Account → Security → 2-Step Verification → App Passwords

---

### Step 3: Run

```bash
docker-compose up -d
```

---

### 🌐 Open in Browser

http://localhost:8080

---

## 🛑 Stop the App

```bash
docker-compose down
```

---

## ⚠️ Important

- Never share your real credentials publicly
- Keep `docker-compose.yml` private after filling credentials

