# Notification System Configuration

## Channels Supported

### Email Notifications
- Trigger: User signup, password reset, order confirmation
- Provider: SendGrid / SMTP
- Format: HTML + plain text fallback

### SMS Notifications
- Trigger: OTP, delivery updates, security alerts
- Provider: Twilio
- Format: Plain text, max 160 characters

### Push Notifications
- Trigger: New message, promotion, system alert
- Provider: Firebase Cloud Messaging (FCM)
- Format: Title + body + action URL

## Notification Rules
- Email: sent immediately on trigger
- SMS: sent immediately for OTP, batched for updates
- Push: sent in real time, silenced between 10pm - 8am

## Channel Status
- Email: Active
- SMS: Active
- Push: Active
