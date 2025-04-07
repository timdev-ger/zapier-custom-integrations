# 🔌 Zapier Custom Integrations Hub

Welcome to the Zapier Custom Integrations Hub!  
This repository contains custom-built Zapier integrations for platforms that don't yet offer an official Zapier app — including **ERP**, **CRM**, **E-Commerce**, and other business tools.

Built using the **Zapier Platform CLI** with **JavaScript**.

---

## 📁 Project Structure

```bash
/integrations  # Completed Zapier integrations
/requests      # Community-submitted requests for new integrations
```

---

## ✅ Available Integrations

- [Shopware 6](./integrations/shopwarev6)  
→ Includes searches for Customers, Orders, Sales Channels, Customer Groups and actions like Create Customer, Create Order, etc.

> More integrations coming soon...

---

## 📬 Request a New Integration

Want to see your favorite platform supported?  
Create a new `.md` file inside the `/requests` folder using [this template](./requests/template.md), and submit a pull request.

Please include:
- A link to the API documentation
- Test account credentials (if possible)
- A short platform description
- A list of desired **Triggers**, **Actions**, and **Searches**

Example: [`template.md`](./requests/template.md)

---

## 🛠️ Needed Tech Stack

- OAuth2 / API Key / Basic Auth supported
