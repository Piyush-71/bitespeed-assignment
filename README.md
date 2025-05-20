# Bitespeed Identity Reconciliation Backend

This is a backend service for identifying and tracking customer identities across multiple purchases, using email and phone number reconciliation.

## 📌 Problem Statement

In real-world scenarios, a single user might interact with a business using different identities — email or phone number. This backend service helps resolve those identities and returns a consistent primary contact.

## 🔗 Hosted Endpoint

The service is live at:

https://bitespeed-2gui.onrender.com/identify


## 🚀 How to Use

Send a `POST` request to the `/identify` endpoint with a **JSON body** (not form-data) in the following format:

```json
{
  "email": "foo@bar.com",
  "phoneNumber": "1234567890"
}
