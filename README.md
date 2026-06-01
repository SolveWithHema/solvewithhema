# Hema Anand — SolveWithHema

**Full-stack developer** with enterprise systems experience and a passion for building production-deployed web applications — from ASP.NET Core MVC platforms with clean architecture to AI-integrated client-facing sites and REST APIs.

💼 [LinkedIn](https://www.linkedin.com/in/hemaanand/) &nbsp;|&nbsp; 💻 [GitHub](https://github.com/SolveWithHema)

---

## 🚀 Live Projects

### 🎂 Edible Art by Hema
**Full-stack ASP.NET Core MVC web application**
🔗 [edibleartbyhema.com](https://edibleartbyhema.com)
🗓 Launched March 19th 2026 — actively developed, iterating with agile methodology

![C#](https://img.shields.io/badge/C%23-60%25-239120?style=flat-square&logo=csharp&logoColor=white)
![HTML](https://img.shields.io/badge/HTML%2FCSS-20%25-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-10%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-10%25-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-App%20Service%20%7C%20SQL%20%7C%20Blob-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

A production-quality, full-stack platform built around a custom edible art brand — showcasing real-world C# development through clean architecture, a fully managed cloud database, and a secure admin CMS. Runs on live production Azure infrastructure.

| Layer | Technology |
|---|---|
| Framework | ASP.NET Core MVC (.NET 8) |
| Language | C# |
| Database | Azure SQL Database |
| ORM | Entity Framework Core 8 |
| Auth | Cookie Authentication + Claims Identity |
| Frontend | Bootstrap 5, HTML5, CSS3, JavaScript |
| Storage | Azure Blob Storage |
| Architecture | Clean Architecture, Dependency Injection |
| Hosting | Azure App Service |
| Deployment | Visual Studio Publish → Azure App Service |
| Domain & DNS | GoDaddy (domain registration) + Cloudflare (DNS, CDN, SSL) |

**Solution structure (3-project clean architecture):**
```
EdibleArtByHema.sln
├── EdibleArtByHema.Web      ← Public-facing portfolio site
├── EdibleArtByHema.Core     ← Shared models, EF Core DbContext, services (private)
└── EdibleArtByHema.Admin    ← Secure content management app (private)
```

**Highlights:**
- Production Azure infrastructure — Azure App Service, Azure SQL Database, and Azure Blob Storage (self-managed)
- Self-funded at minimal cost — Azure free tier with Cloudflare handling domain routing
- Azure Blob Storage for image uploads — integrated across Web and Admin projects
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
🗓 Launched April 8th 2026 — actively developed, iterating with agile methodology

![HTML](https://img.shields.io/badge/HTML-45%25-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-40%25-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-15%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-Static%20Web%20Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-DNS%20%7C%20CDN%20%7C%20SSL-F38020?style=flat-square&logo=cloudflare&logoColor=white)

A fully responsive site for a portrait and lifestyle photographer — handling end-to-end client booking from package browsing to Calendly scheduling to deposit confirmation.

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Google Fonts (Cormorant Garamond, Jost) |
| Booking | Calendly Inline Widget (dynamic multi-event) |
| Hosting | Azure Static Web Apps (Free tier) |
| CI/CD | GitHub Actions (auto-deploy on push) |
| Domain & DNS | Cloudflare (domain registration, DNS, CDN, SSL, AI bot protection) |

**Highlights:**
- Dynamic Calendly integration — each package card loads its own event type into a single inline embed
- Self-funded at minimal cost — production-deployed on Azure free tier
- `IntersectionObserver`-based scroll reveal animations with staggered entrance effects
- Mobile-first responsive layout with hamburger nav, photo collage hero, and hover lift effects
- Deposit flow — Venmo & PayPal links for clients to confirm booking after Calendly selection
- Custom domain via Cloudflare DNS (CNAME) + Azure custom domain verification with auto-provisioned SSL

---

### 🖊️ Notary Services — Hema Anand
**AI-powered booking & information site for a live notary services business**
🔗 [notaryservices.hemaanand.com](https://notaryservices.hemaanand.com)
🗓 Launched June 1st 2026 — live production

![HTML](https://img.shields.io/badge/HTML-35%25-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-40%25-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-25%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-Static%20Web%20Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20AI-FAQ%20Chatbot-4285F4?style=flat-square&logo=google&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-DNS%20%7C%20CDN%20%7C%20SSL-F38020?style=flat-square&logo=cloudflare&logoColor=white)

A fully static, production-deployed booking site for a commissioned NC Notary Public — integrating AI, geolocation, serverless forms, and automated appointment tracking. Hosted at $0/month.

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Chatbot | Google Gemini API (gemini-2.5-flash) |
| Geolocation | OpenStreetMap Nominatim API — NC address validation, haversine distance calc, IRS mileage logic |
| Booking Form | Web3Forms (serverless, no backend) |
| Appointment Log | Google Sheets API |
| Hosting | Azure Static Web Apps (Free tier) |
| CI/CD | GitHub Actions (auto-deploy on push) |
| Domain & DNS | Cloudflare (DNS, CDN, SSL, AI bot protection) |

**Highlights:**
- Gemini AI-powered FAQ chatbot — scoped to notary services context, answers client questions 24/7
- Geolocation engine — validates NC-only addresses, calculates distance from Morrisville using haversine formula, applies IRS federal business mileage rate for travel fee logic
- Serverless booking form via Web3Forms — submissions delivered to email, no backend required
- Google Sheets API integration — every booking auto-logged for appointment tracking
- Policy gate — clients must open and acknowledge booking policies PDF before submitting
- $0/month hosting — Azure Static Web Apps free tier + Cloudflare free tier

---

## 🔒 Private Repositories

All repos are available for review upon request.

| Repository | Description | Stack |
|---|---|---|
| **EdibleArtByHema.Core** | Shared class library — EF Core DbContext, models, `IArticleService`, async repository pattern, custom `IAppLogger` | C#, EF Core 8, Azure SQL |
| **EdibleArtByHema.Admin** | Secure internal CMS — full CRUD, image uploads to Azure Blob, featured toggle, JSON data migration tool | ASP.NET Core MVC, C#, Cookie Auth |
| **EdibleArtByHema.Web** | Public web app source (live at edibleartbyhema.com) | ASP.NET Core MVC, Bootstrap 5 |
| **HannahMidhaPhotography** | Booking site source (live at photography.hannahmidha.com) | HTML, CSS, JS, Azure Static Web Apps |
| **NotaryServices** | Notary site source (live at notaryservices.hemaanand.com) | HTML, CSS, JS, Gemini AI, Azure Static Web Apps |

> 💬 Happy to walk through any of these via live screen share or grant private repo access — just reach out.

---

## 💼 Prior Experience

**Systems Programmer Analyst** — College Foundation Inc (Client: NCSEAA — NC State Education Assistance Authority)

Long-tenure role spanning multiple waves of legacy modernization, enterprise integrations, and managing public-facing web portals across NCSEAA domains — assisting NC K-12 and higher education students, families and schools.

- **Web Portals** — Built and maintained public-facing portals serving NC students, families, K-12 and higher education institutions
- **Legacy Modernization (Multiple Waves)** — Successive modernization cycles: VBA → ASP.NET, iSeries / RPG → Java / Tomcat → ASP.NET Core / C#
- **DocuSign eSignature** — Connect API, JSON webhooks, envelope automation, bulk sends, account admin
- **Azure** — Queue Storage, message-driven architecture
- **IIS** — Application configuration and deployment
- **Integrations** — REST APIs, JSON webhooks, enterprise workflow automation
- **Mixed Stack** — ASP.NET, Java, Classic ASP across multiple systems and modernization phases

Each modernization wave brought new technologies, new architecture patterns, and new integration challenges — building a foundation that spans legacy systems, modern cloud, and everything in between.

---

## 🛠 Tech Stack

```
Backend        C# · ASP.NET Core MVC (.NET 8)
Database       Azure SQL Database · Entity Framework Core 8
Auth           Cookie Authentication · Claims Identity
Frontend       HTML5 · CSS3 · JavaScript · Bootstrap 5
AI / APIs      Google Gemini API · Web3Forms · Google Sheets API · OpenStreetMap Nominatim API
Cloud          Microsoft Azure · Azure App Service · Azure Static Web Apps · Azure Blob Storage · Azure SQL
CI/CD          GitHub Actions
Patterns       Clean Architecture · Dependency Injection · Repository Pattern
Tools          Git · Calendly · EF Core Migrations
DNS/CDN        Cloudflare · GoDaddy — domain registration, DNS, CDN, SSL (self-managed)
Enterprise     DocuSign Connect API · Azure Queue Storage · IIS · JSON Webhooks · iSeries/RPG
```

---

## 📬 Contact

Open to full-stack, backend (.NET/C#), AI integration, and frontend roles.

💼 [LinkedIn](https://www.linkedin.com/in/hemaanand/) &nbsp;|&nbsp; 💻 [GitHub](https://github.com/SolveWithHema) &nbsp;|&nbsp; 🌐 [edibleartbyhema.com](https://edibleartbyhema.com) &nbsp;|&nbsp; 🖊️ [notaryservices.hemaanand.com](https://notaryservices.hemaanand.com)
