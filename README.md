# 🛒 Umbraco Noon E-Commerce App

A modern e-commerce demo built with **Umbraco CMS v15** and **.NET 9**, using **Umbraco Commerce** for product and order management.

---

## 🔍 Overview

This demo showcases a fully functional online store with a customizable storefront and admin dashboard. Ideal for learning or kickstarting an Umbraco-based e-commerce project.

---

## 🖼️ Screenshots

### 🏠 Storefront

<div style="text-align: center;">
    <img src="images/project-overview.gif" style="border-radius: 20px; width: 100%;" alt="Storefront Screenshot" />
</div>

### ⚙️ Admin Dashboard

<div style="text-align: center;">
    <img src="images/cms.gif" style="border-radius: 20px; width: 100%;" alt="Backoffice Screenshot" />
</div>

---

## 🚀 Quick Start

1. **Open in Visual Studio**
   Launch `Umbraco.Commerce.DemoStore.sln`.

2. **Set Startup Project**
   Right-click `Umbraco.Commerce.DemoStore.Web` → **Set as StartUp Project**.

3. **Run the Site**
   Press `Ctrl + F5`.

---

### 🔄 (Optional) Import Sample Database

1. Import `.\db\UmbracoCommerceDemoStore_v15.bacpac`.
2. Update your `appsettings.json`:

```json
"ConnectionStrings": {
  "umbracoDbDSN": "Server=.;Database=UmbracoCommerceDemoStore_v15;User Id=your_user;Password=your_pass;TrustServerCertificate=true;",
  "umbracoDbDSN_ProviderName": "Microsoft.Data.SqlClient"
}
```

---

## 🔐 Admin Login

- **Email:** `admin@example.com`
- **Password:** `password1234`

---

## 🧰 Tech Stack

- **Umbraco CMS v15**
- **Umbraco Commerce**
- **.NET 9**
- **SQL Server**
