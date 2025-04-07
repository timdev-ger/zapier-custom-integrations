# 📡 Integration Request: Shopware 6

## 🔗 API Documentation
[Link](https://shopware.stoplight.io/docs/admin-api/docs/introduction/Shopware%206%20Admin%20API.md)

## 🧪 Access / Test Account
- Demo credentials available via Shopware's public demo or your own test instance.
- You can set up a test shop at [https://www.shopware.com/en/demo/](https://www.shopware.com/en/demo/)
- Authentication: OAuth2 (client credentials flow)

## 🧩 Platform Overview
**Name:** Shopware 6  
**Category:** E-Commerce  
**Description:**  
Shopware 6 is a flexible and modern e-commerce platform designed for merchants of all sizes. It offers a powerful Admin API that supports deep integration with external services, making it ideal for custom workflows and automation via Zapier.

## 🛠️ Requested Functionality

### ✅ Searches
- `Find Sales Channel`: Retrieve sales channels by ID or name
- `Find Customer Group`: Look up customer groups
- `Find Customer`: Search for a customer by email or ID
- `Find Order`: Retrieve order data by ID or other parameters

### ✅ Actions
- `Create Customer`: Push a new customer into Shopware
- `Create Customer Group`: Add a new customer group
- `Create Order`: Submit a new order to Shopware

### 🚫 Triggers
- No triggers implemented yet

## 📌 Additional Notes
- Auth handled via OAuth2 client credentials
- Rate limiting depends on the server (self-hosted or cloud)
- No official Zapier integration exists, so this custom app allows tailored automations (e.g. syncing customers/orders from other platforms)
