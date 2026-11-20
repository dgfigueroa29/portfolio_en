<div align="center">

# David Figueroa

**Android Tech Lead · 18 years building software that has to work where the signal fails**

Kotlin · Jetpack Compose · KMP · Node.js · AWS · AI and agent adoption

[faro.net.ar](https://faro.net.ar) · [LinkedIn](https://www.linkedin.com/in/david-figueroa-mentor-faro-android-ia) · [CV](https://faro.net.ar/recursos) · [david@faro.net.ar](mailto:david@faro.net.ar)

</div>

---

**70+ projects · 14 organizations · 4 regulated or critical domains**
Fintech under BCRA rules · clinical software with CE, GDPR and CatSalut · cash-in-transit logistics · field operation without connectivity.

---

## How to read this portfolio

Every entry states the **year** and the **type of engagement**. Most portfolios leave both out, and without them "70 projects" means nothing.

| | Engagement |
|---|---|
| 🏢 | Work for an organization, as an employee or a full-time contractor |
| 🔦 | FARO portfolio, my independent consultancy |
| 🚀 | My own product |

Where work came through an intermediary, both appear: **who contracted me** and **the end client**.

---

## Selected work

### 🏢 Ncuenta · NaranjaX · 2021–2023
**Regulated fintech · 15-person team**

A digital wallet had to become a fintech regulated by Argentina's Central Bank. That meant rebuilding Onboarding, identity verification (KYC) and anti-money-laundering (AML) without losing users along the way: every new regulatory requirement is one more step where someone drops off.

I led the CVU-to-CBU migration as Mobile Tech Lead, coordinating Android, Backend and iOS with Scrum of Scrum. **User conversion went from 70% to 90%.**

We also added accessibility with TalkBack and its iOS equivalent for blind users, plus anti-fraud improvements with biometric validation.

[Google Play](https://play.google.com/store/apps/details?id=com.tarjetanaranja.ncuenta)

---

### 🏢 Xsales · Apex Global Mobility | Grupo Mariposa · 2024–present
**Field sales for Bia, PepsiCo and associated brands · 9 countries · offline first**

Two applications sharing one monorepo. **Asesor** is the sales rep's tool: pre-sales, credit management, portfolio, products, routes, loyalty and customer service. **Líder** is the supervisor's tool for running that sales team, and it is the product I have led technically since August 2026.

**Roadmap delivery above 85% per quarter**, a level the team had not sustained before, with field operation never interrupted.

Sales reps working in areas without coverage, syncing whenever they find it. The entire design revolves around that constraint.

**Monorepo consolidation.** It was a key result for the period. Estimated at two months, shipped in one. Together with the cross-functional team we defined the shared-module segregation criteria. **Líder was then built on top of that foundation** as the third app in the ecosystem: the architecture did not just unify what existed, it made a new product possible. The real cost was synchronizing in-flight releases, features and fixes across several instances; the cheaper fix was a mechanism to unify shared library versions without cross-app impact.

**Realm to Couchbase Lite migration.** Forced by SDK deprecation. We underestimated how similar the two would be: real work went into replication, scale, indexes, query optimization, drain and Room caching. Field operation was never interrupted.

**AI adoption.** I brought Claude, Gemini and Microsoft Copilot into the team's development cycle.

---

### 🏢 Muvin · Bolsa de Comercio de Rosario, through Alternativas Inteligentes (now SaiLO) · 2023–2024
**Agribusiness · leading 10 people**

An agricultural logistics platform covering swine, grain and fertilizers, with several verticals served by one team.

The problem wasn't technical at first: every release dragged **up to three hotfixes** and the team lost half a sprint to rework. People were assigned to two and three projects at once, without focus or priority.

I reorganized the area into delivery cells with per-project focus, introduced Git Flow, release trains and Scrum, and made QA the owner of validation. **Releases started shipping clean**, first per sprint and later monthly. The changes began in the second half of my first month.

In parallel I led the architectural and modular migration of the platform for performance, observability and quality, and started the move to Node.js while training the team.

`Angular` `PWA` `micro frontends` `PHP` `Node.js` `MySQL` `SSO` `SAML`

---

### 🔦 wtswrng · Mangrana Ventures and Setfile, Barcelona · 2021–2024
**Clinical software in production**

A health app that generates presumptive diagnosis, in use at private clinics in Barcelona. **CE, GDPR and CatSalut** requirements met.

Accessibility was not an optional layer: the interface is entirely illustrated, **without words, gender, language or age**, so it works with whichever patient is in front of it.

They first knew me as a CloudX client, then continued the account directly with me for three years.

---

### 🏢 CloudX · 2020–2021
**Infrastructure cost reduction**

**−80% cloud cost on AWS.** Three fronts: decoupling oversized resources, aligning scale to the product's real demand, and using free tiers and startup plans. The fixed remainder after all adjustments settled at 20%.

I also implemented SDUI and BFF with AWS Lambda, which allowed UI updates without redeployment.

Products: Librology, a readers and authors social network; and symptom checkers.

---

### 🔦 BA Agentes, BA Móvil and Paradas de Colectivos · City of Buenos Aires Government, through Kwan Mobile · 2016–2019
**Civic tech at city scale**

Three systems for the Government of the City of Buenos Aires: traffic violation management for officers on the street, public transport stop surveying, and a citizen-facing view of traffic status, flights and driving directions.

Almost three years of sustained work with the end client through the contracting party.

---

### 🏢 Genesis Mobile · Prosegur, through Tecsol Group · 2021
**Cash-in-transit logistics · Europe and Latin America**

Cash and goods handling apps with heavy barcode and QR scanning in street operation.

**−30% scanning time**, through a library change, improvements to internal components, and adjustments to how the app communicated with the other devices in the flow. **−25% server communication time.**

The library comparison behind that number is published as a POC: see **DemoScan**, now evolved into WhyScan.

---

## 🚀 Own products · FARO

| Product | Status | What it validates |
|---|---|---|
| **WhyScan** | [Play Store](https://play.google.com/store/apps/details?id=ar.net.faro.whyscan) · released | Compose Multiplatform, offline first, accessibility and AI agent assistance. No account, no tracking, no telemetry. Evolves the DemoScan POC across Zxing, Quickie and Scandit |
| **Dynamic** | POC in progress | Kotlin, Compose and Material3 with BFF and SDUI for a design system |
| **Salto Inicial** | [Google Play](https://play.google.com/store/apps/details?id=com.boa.saltoinicial) | All of Mendoza's basketball: live results, reports and interviews |
| **faro.net.ar** | In production | My own site, built with Astro. Private source |

---

## Sustained capabilities

These are not technologies I learned once. They are problems I have kept solving across different organizations over the years.

**Operation without connectivity** — Adecoagro 2013, rural estate access control with QR scanning and deferred sync · Prosegur 2021, scanning in cash-in-transit logistics · Apex Global Mobility | Grupo Mariposa 2024, field sales with Couchbase Lite · WhyScan 2026.

**Real accessibility** — wtswrng, an interface that does not depend on language or literacy · NaranjaX, TalkBack and its iOS equivalent · WhyScan, as an explicit product goal.

**Regulatory compliance** — BCRA rules in Argentine fintech · CE, GDPR and CatSalut in Spanish clinical software.

**AI adoption with method** — executable specifications, MCP agents and output verification. Comparing delivery estimates with and without assistance across three organizations, work shipped up to 40% earlier. That figure comes from estimates, not measured throughput. It holds with cheaper models: the gain comes from the method, not from token spend.

---

## Full catalogue

### 🏢 Work for organizations

| Years | Organization | Projects |
|---|---|---|
| 2024– | Apex Global Mobility \| Grupo Mariposa | Asesor · pre-sales, credit, portfolio, routes and loyalty for sales reps; Líder · sales team supervision. Bia, PepsiCo and associated brands across 9 countries |
| 2023–2024 | Alternativas Inteligentes (now SaiLO) | Muvin · Bolsa de Comercio de Rosario |
| 2021–2023 | NaranjaX | Ncuenta |
| 2021 | Prosegur, through Tecsol Group | Genesis Mobile |
| 2020–2021 | CloudX | Librology · readers club social network; symptom checkers; Watchman · tracking app for private security |
| 2020 | GlobalLogic | Fixed · surveying and pre-sales for Claro Argentina |
| 2019–2020 | Winecta | Padel Manager, Official Granada Audio Guide, Peep, Creatuaplicacion, school management |
| 2018–2019 | FTL | Infratrack · traffic violations in Lanús and Ezeiza |
| 2017–2018 | Streambe | BPN · promotions, branches, ATMs and home banking; Ethic Compass · conflicts of interest, whistleblowing and surveys; BK · capital goods bond application management; CoberMed · connecting members with their health provider; base app generator portal |
| 2015–2017 | Tween, later Vloom | Vloom · bulk SMS and push notification platform; Tarjeta Naranja; Tarjeta Nevada · migration from PHP 5 to 7, CodeIgniter 2 to 3 and Laravel 4 to 5 across a public site, a secure site and a content panel; Crypto · mobile bitcoin wallet |
| 2013–2015 | Aconcagua Software Factory | Adecoagro, PCG · Pan American Energy, Sanatorio Finochietto, FriendBall, 4coronas, FácilMúsica |
| 2012–2013 | Rumaos | SGRRHH · RedMercosur, SGDOC, SGOP, DNI, ASEGH · hospital management |
| 2009–2012 | Aconcagua Software Factory | Construpages, El Sol Online, Empretur, mendobytes |
| 2009 | BIG SA | Comproaccesorios · e-commerce for the Ford Meschini dealership; bus ticket and tourism portal |
| 2008–2009 | MAIN Sistemas | Custom ERP for Dil Brands; Presenter · advertising presentation portal; IVD · inventory management API; custom websites |

### 🔦 FARO portfolio

| Years | Client | Project |
|---|---|---|
| 2021–2024 | wtswrng · Barcelona | Clinical app for presumptive diagnosis |
| 2024 | Jacidi · Barcelona | Digital signage on Android TV and Chromecast for hotel and gym chains |
| 2023– | FUSAP → QuintoAndar | Technical mentoring for engineering teams |
| 2019 | Me cubro | MeCubro · APIs for cargo transport and personal accident insurance |
| 2019 | Inmoclick | Inmoclick and Inmoclick2 · proptech, Java to Kotlin migration with MVVM and Clean |
| 2019 | Tuten IT | Cabbo · social network and navigation for boat users |
| 2019 | That Day in London | Field pollster and volunteer systems |
| 2018–2019 | iVelopment | Conectate · energy efficiency and renewables |
| 2018–2019 | Ubykuo | Plan Américas · VoIP calling with a prepaid card |
| 2017–2018 | WeChain, for Tween | Cryptocurrency rewards with blockchain on Android |
| 2017–2018 | XRP | XRPSalesWork · catalogue, orders, routes and collections for field sales reps |
| 2017 | FotoSprint | Photo product catalogue with a partner store network |
| 2016–2019 | Kwan Mobile → City of Buenos Aires | BA Agentes, BA Móvil, Paradas de Colectivos |
| 2016–2017 | Viewpoints | Argentina's National Weather Service · weather visualization and forecasting; tourism and marketing apps |
| 2016 | Software Factory | Sage · app for field interviewers |
| 2014–2015 | Goddy | Goody · social network connecting athletes with related products |
| various | Own builds and prototypes | RentAtablet · event guest management; Woman · supporting women with executive careers; Chapi, AjustAR and TraslatorChat · alphas |

---

## Where I write

The criteria I use to choose architecture and to evaluate code are public:

- [Android architecture 2026: patterns that actually hold](https://faro.net.ar/blog/arquitectura-android-2026)
- [How to evaluate code quality as a technical lead](https://faro.net.ar/blog/calidad-codigo-lideres-tecnicos)

Services and case work at [faro.net.ar/portfolio](https://faro.net.ar/portfolio); CV and resources at [faro.net.ar/recursos](https://faro.net.ar/recursos).

---

## Let's work together

I am open to remote or hybrid opportunities from Mendoza, Argentina, and to consulting engagements through FARO.

**[david@faro.net.ar](mailto:david@faro.net.ar)** · **[faro.net.ar](https://faro.net.ar)** · **[LinkedIn](https://www.linkedin.com/in/david-figueroa-mentor-faro-android-ia)**

<div align="right"><sub>Last reviewed: 2026-11 · <a href="https://github.com/dgfigueroa29/portfolio">Versión en español</a></sub></div>
