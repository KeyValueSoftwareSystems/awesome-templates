# Awesome Communication Templates

_Brought to you by [trysiren.io](https://trysiren.io)_

A collection of ready-to-use message templates for every business scenario—across all your favorite channels.

## What is this?

This repository contains a comprehensive set of communication templates for:
- **Email**
- **SMS**
- **WhatsApp**
- **Slack**
- **Microsoft Teams**
- **Push notifications**

Each template is designed for a specific use case (like fraud alerts, appointment reminders, onboarding, and more) and is ready to copy, adapt, and use in your own systems.

Want a sneak peek? Browse live previews of all templates at [trysiren.io/templates](https://trysiren.io/templates).

## Why use these templates?
- **Save time:** No need to write messages from scratch for every channel.
- **Consistency:** Ensure your communications are clear and professional everywhere.
- **Multi-channel:** Templates are tailored for each channel’s best practices and formatting.
- **Inspiration:** Browse for ideas and adapt to your needs.

## How to use
1. **Browse the folders** by business area (e.g., `finance/`, `customer-support/`, `marketing/`).
2. **Find your use case** (e.g., `fraud_alert_critical`).
3. **Open the `default.yaml`** inside the `official/` folder.
4. **Copy the template** for your preferred channel (email, SMS, etc.).
5. **Customize** the variables (like `{{account_number}}`, `{{timestamp}}`, etc.) for your needs.

You can use these templates directly in your codebase, automation tools, or communication platforms.

## Example
Here’s a snippet from a critical fraud alert template:

```yaml
channels:
  email:
    subject: "🚨 Fraud Alert on {{account_number}} – Immediate Attention Required"
    body: |
      Hi there,
      We’ve detected a potentially fraudulent charge on your account **{{account_number}}**:
      • Amount: {{transaction_amount}}
      • Merchant: {{merchant_name}}
      ...
  sms:
    text: >
      FRAUD ALERT 🚨 Acct {{account_number}}: {{transaction_amount}} at {{merchant_name}}. Risk {{risk_score}}. {{action_required}}.
```

## Contributing
Have a template to share? Open a pull request!

---

*Use, adapt, and ship better messages—across every channel.*

---

[Centralize, automate, and streamline your notifications](https://trysiren.io)

Build and manage beautiful, effective notifications across SMS, email, push, Slack, chat, and more.
