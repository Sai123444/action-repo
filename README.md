# action-repo

# 🔧 GitHub Action Repo (Webhook Trigger)

This is a dummy GitHub repository used to **trigger webhook events** (Push, Pull Request, Merge) for the companion project: [`webhook-repo`](https://github.com/Sai123444/webhook-repo).

---

## 🔗 Purpose

Used for testing and simulating:

- ✅ Push events
- ✅ Pull Request events
- ✅ Merge events (Bonus)

These events are sent to a webhook listener (Flask server) and stored in MongoDB, where they’re displayed on a live updating frontend.

---

## 🚀 How to Trigger Events

1. **Push**  
   Edit any file (e.g., `README.md`) and push to main

2. **Pull Request**  
   - Create a new branch
   - Make a change
   - Open a PR from new branch → main

3. **Merge** (Optional)  
   - After PR is opened, click **Merge pull request**

Each of these triggers a webhook to:

```txt
https://<your-ngrok-url>.ngrok-free.app/webhook
📂 Related Repo
👉 Webhook Listener App (webhook-repo)

✉️ Author
Sreesai Malli
📧 mallisreesai2004@gmail.com
🔗 GitHub

