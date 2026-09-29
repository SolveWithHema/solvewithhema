# Hema Anand | SolveWithHema

Full-stack .NET developer with 20+ years of enterprise experience, now building and running production web applications on Azure. I work across the stack, from ASP.NET Core MVC platforms with clean architecture to AI-integrated client sites and third-party API integrations.

[LinkedIn](https://www.linkedin.com/in/hemaanand/) &nbsp;|&nbsp; [GitHub](https://github.com/SolveWithHema)

---

## Live Projects

### Edible Art by Hema
**Full-stack ASP.NET Core MVC web application**
[edibleartbyhema.com](https://edibleartbyhema.com) &nbsp;·&nbsp; Site live since March 19, 2026. Actively developed in agile iterations.

![.NET](https://img.shields.io/badge/.NET-10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-App%20Service%20%7C%20SQL%20%7C%20Blob-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

A production platform built for an upcoming edible art business, with clean architecture, a managed cloud database, and a secure admin CMS. Began as a portfolio piece and growing into the site the business runs on.

| Layer | Technology |
|---|---|
| Framework | ASP.NET Core MVC (.NET 10) |
| Language | C# |
| Database | Azure SQL Database |
| ORM | Entity Framework Core 10 |
| Auth | Cookie Authentication, Claims Identity |
| Frontend | Bootstrap 5, HTML5, CSS3, JavaScript |
| Storage | Azure Blob Storage |
| Architecture | Clean Architecture, Dependency Injection, Repository Pattern |
| Hosting | Azure App Service |
| Deployment | Visual Studio Publish to Azure App Service |
| Domain & DNS | GoDaddy (registration), Cloudflare (DNS, CDN, SSL) |

**Solution structure (3-project clean architecture):**
```
EdibleArtByHema.sln
├── EdibleArtByHema.Web      Public-facing site
├── EdibleArtByHema.Core     Shared models, EF Core DbContext, services
└── EdibleArtByHema.Admin    Secure content management app
```

**Highlights:**
- Migrated all three projects from .NET 8 to .NET 10 with EF Core 10, using a tagged rollback point for safe deployment
- Azure Blob Storage image uploads shared across the Web and Admin projects
- Shop page with interactive order builders and pricing logic
- SQL-driven featured creations carousel and full-text search across articles, tags, and descriptions
- Interactive Platter Builder: select ingredients and discover matching dishes
- *Surprise Me* mystery basket feature, inspired by the show Chopped
- Admin CMS with full CRUD, image upload, featured toggle, and a JSON data migration tool
- Async `IArticleService` repository, custom file logger, and code-first EF Core migrations

---

### Hannah Midha Photography
**Portfolio and client booking site**
[photography.hannahmidha.com](https://photography.hannahmidha.com) &nbsp;·&nbsp; Launched April 8, 2026

![Azure](https://img.shields.io/badge/Azure-Static%20Web%20Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

A responsive site for a portrait and lifestyle photographer that handles the full client booking flow, from browsing packages to Calendly scheduling to deposit confirmation.

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Booking | Calendly inline widget (dynamic, multi-event) |
| Hosting | Azure Static Web Apps |
| CI/CD | GitHub Actions (auto-deploy on push) |
| Domain & DNS | Cloudflare (registration, DNS, CDN, SSL, AI bot protection) |

**Highlights:**
- Each package card loads its own Calendly event type into a single inline embed
- Deposit confirmation step after scheduling
- Scroll-reveal animations built on `IntersectionObserver` with staggered entrances
- Mobile-first layout with hamburger navigation and a photo collage hero
- Custom domain via Cloudflare CNAME and Azure domain verification with auto-provisioned SSL

---

### Notary Services
**AI-assisted booking and information site for a live notary business**
[notaryservices.hemaanand.com](https://notaryservices.hemaanand.com) &nbsp;·&nbsp; Launched June 1, 2026

![Azure](https://img.shields.io/badge/Azure-Static%20Web%20Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20API-FAQ%20Chatbot-4285F4?style=flat-square&logo=google&logoColor=white)

A static, production-deployed site for a commissioned NC Notary Public, combining an AI chatbot, geolocation-based pricing, serverless forms, and automated appointment logging.

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Chatbot | Google Gemini API (gemini-2.5-flash) |
| Geolocation | OpenStreetMap Nominatim API |
| Booking Form | Web3Forms (serverless) |
| Appointment Log | Google Sheets API |
| Hosting | Azure Static Web Apps |
| CI/CD | GitHub Actions (auto-deploy on push) |
| Domain & DNS | Cloudflare (DNS, CDN, SSL, AI bot protection) |

**Highlights:**
- Gemini-powered FAQ chatbot scoped to notary services, answering client questions around the clock
- Travel fee engine that validates NC-only addresses, calculates distance with the haversine formula, and applies the IRS business mileage rate
- Serverless booking form with every submission auto-logged to Google Sheets
- Policy gate requiring clients to open and acknowledge the booking policies before submitting
- Runs entirely on free-tier Azure and Cloudflare hosting

---

## Private Repositories

Source code for these projects is kept private. I'm happy to walk through any of it on a screen share or grant read access on request.

| Repository | Description | Stack |
|---|---|---|
| **EdibleArtByHema.Core** | Shared class library: EF Core DbContext, models, `IArticleService`, async repository pattern, custom `IAppLogger` | C#, EF Core 10, Azure SQL |
| **EdibleArtByHema.Admin** | Secure internal CMS: full CRUD, Azure Blob image uploads, featured toggle, JSON data migration tool | ASP.NET Core MVC, C#, Cookie Auth |
| **EdibleArtByHema.Web** | Public web app | ASP.NET Core MVC, Bootstrap 5 |
| **HannahMidhaPhotography** | Booking site | HTML, CSS, JS, Azure Static Web Apps |
| **NotaryServices** | Notary booking site | HTML, CSS, JS, Gemini API, Azure Static Web Apps |

---

## Prior Experience

**Systems Programmer Analyst**, College Foundation Inc. (Client: NC State Education Assistance Authority)

A long-tenure role spanning several waves of legacy modernization, enterprise integrations, and public-facing web portals serving NC K-12 and higher education students, families, and schools.

- **Web Portals:** Built and maintained statewide portals for students, families, and K-12 and higher education institutions
- **Legacy Modernization:** Successive modernization cycles from VBA to ASP.NET, and from iSeries/RPG to Java/Tomcat to ASP.NET Core and C#
- **DocuSign eSignature:** Connect API, JSON webhooks, envelope automation, bulk sends, account administration
- **Azure:** Queue Storage and message-driven, async processing
- **Integrations:** REST APIs, JSON webhooks, enterprise workflow automation
- **Deployment:** IIS application configuration and deployment across ASP.NET, Java, and Classic ASP systems

---

## Tech Stack

```
Backend        C#, ASP.NET Core MVC (.NET 10), Web API
Database       Azure SQL Database, SQL Server, Entity Framework Core 10
Auth           Cookie Authentication, Claims Identity
Frontend       HTML5, CSS3, JavaScript, Bootstrap 5
AI / APIs      Google Gemini API, Google Sheets API, Web3Forms, OpenStreetMap Nominatim, Calendly
Cloud          Azure App Service, Azure Static Web Apps, Azure Blob Storage, Azure Queue Storage, Azure SQL
CI/CD          GitHub Actions
Patterns       Clean Architecture, Dependency Injection, Repository Pattern
DNS/CDN        Cloudflare, GoDaddy
Enterprise     DocuSign Connect API, IIS, JSON Webhooks, iSeries/RPG
```

---

## Contact

Open to full-stack and backend .NET/C# roles in the Raleigh-Durham area and remote.

[LinkedIn](https://www.linkedin.com/in/hemaanand/) &nbsp;|&nbsp; [GitHub](https://github.com/SolveWithHema) &nbsp;|&nbsp; [edibleartbyhema.com](https://edibleartbyhema.com) &nbsp;|&nbsp; [notaryservices.hemaanand.com](https://notaryservices.hemaanand.com)
