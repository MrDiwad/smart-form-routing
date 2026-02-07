# 🎯 Smart Contact Form with AI Routing

A modern contact form that automatically categorizes messages using AI and sends them to Discord.

## 🚀 What Does It Do?

1. User fills out a contact form on a nice landing page
2. Form sends data to n8n (automation tool)
3. AI (Groq) analyzes the message and decides:
   - **Category**: complaint, return request, or other
   - **Urgency**: 1-5 scale
4. Message gets posted to Discord with all the info
5. User sees a "Thank You" page

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: n8n workflow automation
- **AI**: Groq API for smart categorization
- **Notifications**: Discord webhooks

## ✨ Features

- Clean, responsive design
- Real-time form validation
- AI-powered message analysis
- Automatic Discord notifications
- Smooth redirect after submission

## 📸 How It Looks

**Landing Page** → User fills form  
**AI Processing** → Categorizes message  
**Discord** → Team gets notified with category & urgency  
**Thank You Page** → User gets confirmation  

## n8n Workflow:

<img width="1063" height="563" alt="image" src="https://github.com/user-attachments/assets/2f451d89-428e-4c06-a1bb-0500a9e446da" />
