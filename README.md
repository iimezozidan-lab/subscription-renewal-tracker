# Subscription Renewal Tracker

An automated workflow built with n8n that monitors customer subscriptions and sends renewal reminder emails before subscriptions expire.

## Features

- Monitor active subscriptions automatically
- Check upcoming expiration dates
- Send automated email reminders
- Update reminder status after sending
- Prevent duplicate reminder emails
- PostgreSQL database integration

## Workflow

Schedule Trigger

↓

Get Active Subscriptions

↓

Check Active Status

↓

Check Expiry Date

↓

Send Renewal Reminder

↓

Update Subscription Status

## Tech Stack

- n8n
- PostgreSQL
- SMTP Email
- JavaScript Expressions

## Business Value

- Reduces missed renewals
- Increases customer retention
- Eliminates manual reminder tasks
- Prevents duplicate reminder emails
