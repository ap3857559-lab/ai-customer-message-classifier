# AI Customer Message Classifier

An AI-powered customer message classifier built with **Make.com, OpenAI, Webhooks, and Google Sheets**.

## What It Does

This automation receives a customer's message, uses AI to understand the request, and stores the structured result in Google Sheets.

### Example

**Customer message:**

> I want to book a haircut for Saturday. Are you available?

**AI response:**

```text
Service: Haircut
Intent: Booking inquiry
Action: Check Saturday availability
```

## Workflow

```text
Customer Message
       ↓
    Webhook
       ↓
     OpenAI
       ↓
  Google Sheets
```

## Technologies Used

* Make.com
* OpenAI
* Webhooks
* Google Sheets

## Purpose

This project was created as a practical introduction to **AI automation and no-code workflow development**.

It demonstrates how AI can be used to classify customer requests and determine the appropriate next business action.

## Future Improvements

* Connect to a real booking/availability system
* Automatically respond to customers
* Add more customer service intents
* Connect the workflow to a calendar
* Build a complete automated booking system

