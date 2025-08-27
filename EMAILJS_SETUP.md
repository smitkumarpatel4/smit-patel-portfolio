# EmailJS Setup Guide

## How to Set Up Automatic Email Reception

### Step 1: Create EmailJS Account
1. Go to https://www.emailjs.com/
2. Click "Sign Up" and create a free account
3. Verify your email address

### Step 2: Add Email Service
1. In EmailJS dashboard, go to "Email Services"
2. Click "Add New Service"
3. Choose "Gmail" or "Outlook" (recommended: Gmail)
4. Connect your email account (smitkumarpatel4@outlook.com)
5. Note down your **Service ID** (e.g., "service_abc123")

### Step 3: Create Email Template
1. Go to "Email Templates"
2. Click "Create New Template"
3. Use this template:

**Subject:** Portfolio Contact: {{subject}}

**Message:**
```
Hello Smitkumar Patel,

You have received a new message from your portfolio website:

Name: {{from_name}}
Email: {{from_email}}
Subject: {{subject}}

Message:
{{message}}

---
This message was sent from your portfolio contact form.
```

4. Note down your **Template ID** (e.g., "template_xyz789")

### Step 4: Get Your Public Key
1. Go to "Account" → "API Keys"
2. Copy your **Public Key** (e.g., "user_def456")

### Step 5: Update Your Code
Replace these placeholders in `assets/js/main.js`:

```javascript
// Replace YOUR_PUBLIC_KEY with your actual public key
emailjs.init("user_def456");

// Replace YOUR_SERVICE_ID with your service ID
emailjs.send("service_abc123", "template_xyz789", templateParams)
```

### Step 6: Test Your Form
1. Fill out your contact form
2. Submit the form
3. Check your email - you should receive the message immediately!

## Benefits:
✅ **Automatic email delivery** - No user action required
✅ **Reliable** - Works even if user has no email client
✅ **Professional** - No spam folder issues
✅ **Free** - 200 emails per month free
✅ **Fallback** - Still opens email client if EmailJS fails

## Troubleshooting:
- Check browser console for errors
- Verify all IDs are correct
- Make sure email service is connected
- Check spam folder initially
