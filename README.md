# Wingtip Toys - ASP.NET 4.5 Web Forms Tutorial Project

A follow-along implementation of the Microsoft ASP.NET 4.5 Web Forms tutorial series, building a simplified e-commerce storefront called **Wingtip Toys**.

📚 **Tutorial Source:** [Getting Started with ASP.NET 4.5 Web Forms and Visual Studio 2017](https://learn.microsoft.com/en-us/aspnet/web-forms/overview/getting-started/getting-started-with-aspnet-45-web-forms/introduction-and-overview)

---

## About the Project

The Wingtip Toys application is a simplified online storefront where users can browse products by category, view product details, add items to a shopping cart, and complete purchases via PayPal. An admin role is also included for managing products.

---

## Features Covered

- Web Application Project with Web Forms
- Master Pages and site configuration
- Bootstrap for responsive layout and theming
- Entity Framework 6 Code First with LocalDB
- Strongly-typed data controls and model binding
- Value providers and query string handling
- ASP.NET Identity for membership, authentication, and authorization
- SSL and OAuth (Google login)
- Shopping cart functionality
- PayPal payment integration (sandbox)
- Input validation and unobtrusive validation
- Request validation
- Data annotations
- ASP.NET routing
- Error handling and error logging
- File upload
- Administrator role and access restriction

---

## Prerequisites

- [Visual Studio 2017 or Visual Studio Community 2017](https://visualstudio.microsoft.com/downloads/)
- .NET Framework 4.5.2 (installed automatically with Visual Studio)
- SQL Server LocalDB (included with Visual Studio)

---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   ```

2. **Open the solution**  
   Open `WingtipToys.sln` in Visual Studio.

3. **Restore NuGet packages**  
   Visual Studio should restore packages automatically. If not, go to:  
   **Tools → NuGet Package Manager → Package Manager Console** and run:
   ```
   Update-Package -reinstall
   ```

4. **Build and run**  
   Press `F5` to build and launch the application. The database will be created and seeded automatically on first run.

---

## Project Structure

```
WingtipToys/
├── App_Data/               # Local database files (.mdf)
├── App_Start/              # Route and bundle configuration
├── Catalog/                # Product images
├── Models/                 # Entity Framework models and DbContext
├── Logic/                  # Business logic (cart, payment, etc.)
├── Admin/                  # Admin-only pages
├── Account/                # Login, register, and identity pages
├── Default.aspx            # Home page
├── ProductList.aspx        # Product listing by category
├── ProductDetails.aspx     # Individual product detail page
├── ShoppingCart.aspx       # Shopping cart page
├── Checkout/               # Checkout and PayPal integration pages
├── Site.Master             # Master page / shared layout
├── Web.config              # App configuration and connection strings
└── Global.asax             # Application startup and routing
```

---

## Tutorial Progress

| Section | Status |
|---|---|
| Introduction and Overview | ✅ Complete |
| Create the Project | ✅ Complete |
| Create the Data Access Layer | ✅ Complete |
| UI and Navigation | ✅ Complete |
| Display Data Items and Details | ✅ Complete |
| Shopping Cart | ⬜ Not Started |
| Checkout and Payment with PayPal | ⬜ Not Started |
| Membership and Administration | ⬜ Not Started |
| Error Handling | ⬜ Not Started |
| URL Routing | ⬜ Not Started |
| ASP.NET Identity | ⬜ Not Started |

> Update this table as you complete each section.

---

## Key Technologies

| Technology | Purpose |
|---|---|
| ASP.NET Web Forms 4.5 | Web application framework |
| Entity Framework 6 | Database ORM (Code First) |
| SQL Server LocalDB | Local development database |
| Bootstrap | Responsive UI styling |
| ASP.NET Identity | User authentication and roles |
| PayPal SDK | Payment processing (sandbox) |

---

## Notes

- The PayPal integration uses the **developer sandbox** — no real transactions are made.
- The database is created automatically in the `App_Data` folder on first run via EF Code First migrations and seed data.
- OAuth login is configured for Google but requires your own client ID and secret in `Web.config`.

---

## Resources

- [Full Tutorial Series](https://learn.microsoft.com/en-us/aspnet/web-forms/overview/getting-started/getting-started-with-aspnet-45-web-forms/introduction-and-overview)
- [ASP.NET Web Forms Documentation](https://learn.microsoft.com/en-us/aspnet/web-forms/)
- [Entity Framework 6 Documentation](https://learn.microsoft.com/en-us/ef/ef6/)
- [ASP.NET Identity Documentation](https://learn.microsoft.com/en-us/aspnet/identity/)
- [ASP.NET Forums](https://forums.asp.net/)
