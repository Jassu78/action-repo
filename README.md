# action-repo

This repository is created for the **Developer Assessment Task** to trigger GitHub webhooks for push, pull request, and merge events.

---

## 📌 **Purpose**

This repo is used to:

✅ Perform **push**, **pull request**, and **merge** actions  
✅ Send webhooks to the **webhook-repo Flask endpoint**  
✅ Test and demonstrate end-to-end integration of GitHub webhooks with a backend service and database

---

## ⚙️ **Configured Webhook**

The webhook is configured to send events to:

https://webhook-repo-d3gz.onrender.com/webhook 


### **Events included:**

- Push
- Pull Request
- Merge (via pull request merged status)

---

## 🚀 **How to test**

1. **Clone the repo** to your local machine.
2. Make any changes (e.g. edit README.md) and **push**.
3. Create a **new branch**, make changes, and create a **pull request** to `main`.
4. Merge the pull request if applicable.

Each of these actions triggers a webhook sent to the Flask backend and stores it in MongoDB.

---

## 📁 **Repository structure**

This repo contains:

- `README.md` – project purpose and usage
- Dummy files or basic code files for triggering push/PR events

---

## 👨‍💻 **Author**

- **Name:** Jaswanth Jogi  
- **Assessment:** Developer Webhook Integration Task

---

## 📝 **Notes**

🔹 Ensure the webhook URL is active and reachable.  
🔹 Confirm successful delivery in **GitHub → Settings → Webhooks → Recent Deliveries**.

---
