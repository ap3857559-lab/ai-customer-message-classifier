# Test Examples

This file contains examples used to test the AI customer message classifier.

## Test 1 — Pricing Inquiry

**Customer Message:**

> How much is a haircut?

**AI Classification:**

* Service: Haircut
* Intent: Pricing inquiry
* Action: Provide the current price for a haircut

---

## Test 2 — Booking Inquiry

**Customer Message:**

> I want to book a haircut for Saturday. Are you available?

**AI Classification:**

* Service: Haircut
* Intent: Booking inquiry
* Action: Check Saturday availability

---

## Test 3 — Service Inquiry

**Customer Message:**

> Do you offer beard trimming?

**AI Classification:**

* Service: Beard trimming
* Intent: Service inquiry
* Action: Confirm whether beard trimming is offered

## Result

The automation successfully classified different types of customer messages using:

**Webhook → OpenAI → Google Sheets**

