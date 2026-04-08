# Hema Anand — SolveWithHema

**Full-stack developer** building production-deployed web applications — from ASP.NET Core MVC platforms with clean architecture to client-facing static sites and REST APIs.

💼 [LinkedIn](https://www.linkedin.com/in/hemaanand/) &nbsp;|&nbsp; 💻 [GitHub](https://github.com/SolveWithHema)

---

## 🚀 Live Projects

### 🎂 Edible Art by Hema
**Full-stack ASP.NET Core MVC web application**
🔗 [edibleartbyhema.com](https://edibleartbyhema.com)

A production-quality, full-stack platform built around a custom edible art brand — showcasing real-world C# development through clean architecture, a SQL Server database, and a secure admin CMS.

| Layer | Technology |
|---|---|
| Framework | ASP.NET Core MVC (.NET 8) |
| Language | C# |
| Database | SQL Server 2025 |
| ORM | Entity Framework Core 8 |
| Auth | Cookie Authentication + Claims Identity |
| Frontend | Bootstrap 5, HTML5, CSS3, JavaScript |
| Architecture | Clean Architecture, Dependency Injection |
| Hosting | Azure App Service |
| CI/CD | GitHub Actions |

**Solution structure (3-project clean architecture):**
```
EdibleArtByHema.sln
├── EdibleArtByHema.Web      ← Public-facing portfolio site
├── EdibleArtByHema.Core     ← Shared models, EF Core DbContext, services (private)
└── EdibleArtByHema.Admin    ← Secure content management app (private)
```

**Highlights:**
- SQL-driven featured creations carousel
- Full-text search across articles, tags, and descriptions
- Interactive Platter Builder — select ingredients, discover matching dishes
- *Surprise Me* random mystery basket feature (Chopped!-inspired)
- Admin CMS with full CRUD, image upload, featured toggle, and JSON migration tool
- Repository pattern with async `IArticleService`, custom file logger, code-first EF Core migrations

---

### 📸 Hannah Midha Photography
**Production photography portfolio & client booking site**
🔗 [photography.hannahmidha.com](https://photography.hannahmidha.com)

A fully responsive site for a portrait and lifestyle photographer — handling end-to-end client booking from package browsing to Calendly scheduling to deposit confirmation.

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Google Fonts (Cormorant Garamond, Jost) |
| Booking | Calendly Inline Widget |
| Hosting | Azure Static Web Apps (Free tier) |
| CI/CD | GitHub Actions (auto-deploy on push) |

**Highlights:**
- Dynamic Calendly integration — each package card loads its own event type into a single inline embed
- `IntersectionObserver`-based scroll reveal animations with staggered entrance effects
- Mobile-first responsive layout with photo collage hero and hover lift effects
- Deposit flow via Venmo & PayPal after Calendly selection

---

## 🔒 Private Repositories

All four repos are available for review upon request.

| Repository | Description | Stack |
|---|---|---|
| **EdibleArtByHema.Core** | Shared class library — EF Core DbContext, models, `IArticleService`, async repository pattern, custom `IAppLogger` | C#, EF Core 8, SQL Server |
| **EdibleArtByHema.Admin** | Secure internal CMS — full CRUD, image uploads, featured toggle, JSON data migration tool | ASP.NET Core MVC, C#, Cookie Auth |
| **EdibleArtByHema.Web** | Public web app source (live at edibleartbyhema.com) | ASP.NET Core MVC, Bootstrap 5 |
| **HannahMidhaPhotography** | Booking site source (live on Azure) | HTML, CSS, JS, Azure Static Web Apps |

> 💬 Happy to walk through any of these via live screen share or grant private repo access — just reach out.

---

## 🛠 Tech Stack

```
Backend      C# · ASP.NET Core MVC (.NET 8) · REST APIs · Node.js
Database     SQL Server 2025 · Entity Framework Core 8
Auth         Cookie Authentication · Claims Identity
Frontend     HTML5 · CSS3 · JavaScript · Bootstrap 5 · React
Cloud        Microsoft Azure · Azure App Service · Azure Static Web Apps
CI/CD        GitHub Actions
Patterns     Clean Architecture · Dependency Injection · Repository Pattern
Tools        Git · Calendly · EF Core Migrations
```

---

## 📬 Contact

Open to full-stack, backend (.NET/C#), and frontend roles.

💼 [LinkedIn](https://www.linkedin.com/in/hemaanand/) &nbsp;|&nbsp; 💻 [GitHub](https://github.com/SolveWithHema) &nbsp;|&nbsp; 🌐 [edibleartbyhema.com](https://edibleartbyhema.com)
