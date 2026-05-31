# ERP System

A secure, web-based ERP (Enterprise Resource Planning) application built with HTML, CSS, and JavaScript. Designed in the style of Frappe ERP.

## 🔗 Live Demo
> `https://YOUR_USERNAME.github.io/erp-system/`  
> *(Replace YOUR_USERNAME with your GitHub username after deploying)*

---

## 🚀 Modules

| Module | Description |
|---|---|
| **Sales Orders** | Manage customer orders, track fulfillment and delivery status |
| **Purchase Orders** | Track supplier orders, receipts and procurement workflows |
| **Inventory** | Monitor stock levels, warehouses and item movements |
| **Master Data** | Customers, vendors, items, warehouses and chart of accounts |

---

## 🔐 Security Features

- **Rate limiting** — Locks out after 5 failed login attempts (30 second cooldown)
- **Session timeout** — Auto logout after 15 minutes of inactivity
- **Session warning** — 5-minute countdown warning before auto logout
- **Screen lock** — Blurs dashboard when tab is switched or window minimized
- **Input sanitization** — Strips dangerous characters from all inputs
- **Right-click disabled** — Prevents data scraping on the dashboard
- **CSP meta headers** — Blocks unauthorized external resource loading

---

## 🔑 Demo Credentials

```
Email:    admin@erp.com
Password: Admin@123
```

> ⚠️ Change these credentials before production use.

---

## 📁 Project Structure

```
erp-system/
├── index.html      # Main application (Login + Dashboard)
└── README.md       # This file
```

---

## 🛠️ How to Run Locally

No build tools or dependencies needed. Just open the file:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/erp-system.git

# Open in browser
cd erp-system
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 🌐 Deploy to GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under Branch, select **main** → **/ (root)** → click **Save**
3. Your site will be live at:  
   `https://YOUR_USERNAME.github.io/erp-system/`

---

## ⚠️ Production Notes

This is a **frontend prototype**. For a real production deployment:

- [ ] Add a backend (Node.js / Django / Python Flask)
- [ ] Use JWT tokens for authentication
- [ ] Connect a real database (PostgreSQL / MySQL)
- [ ] Enable HTTPS on your server
- [ ] Move credentials to environment variables
- [ ] Add role-based access control (RBAC)

---

## 📄 License

MIT License — free to use and modify.

---

*Built with ❤️ using HTML, CSS & JavaScript*
