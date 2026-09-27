# Hi, I'm Yusuf 👋

Full-stack / backend-leaning engineer. I like problems with real constraints — legal validity, money, concurrency, delivery guarantees — more than CRUD screens.

## Some of what I've actually built

- **Legally-binding e-signature & official correspondence (KEP):** a Node.js client for Turkey's KEP (Kayıtlı Elektronik Posta) e-Yazışma SOAP API — builds S/MIME packages, signs them with a smart card (AKİS), submits over SOAP, and retrieves signed "delil" (legal evidence) receipts back from the state system.
- **Async job & queue processing:** RabbitMQ (`amqplib`) behind several REST APIs for decoupling slow work (file processing, notifications, background jobs) from the request/response cycle.
- **Transactional email pipelines:** Mailgun-based email flows (verification, password reset, notifications) wired into multiple backends.
- **File storage at scale:** S3-backed uploads using presigned URLs (client uploads directly to S3, backend never proxies the bytes).
- **Production-hardened Express APIs:** JWT + Passport auth, Joi validation, Helmet + rate-limiting + xss-clean, Winston logging, Swagger-documented — the boilerplate I reach for when starting a new service.
- **AI-gated mobile architecture (current project):** a photo-to-nutrition app where the backend is the sole authority on entitlements/quotas/AI access — auth → rate limit → validation → entitlement → budget guard → atomic quota reservation, in that order, before any AI call, with automatic refund on failure.
- **Fullstack apps end to end:** booking/appointment systems, an accounting/invoicing app (products, stock, customers, payments, invoices), an expense tracker (Node/Express/Prisma/Postgres + React/Vite, tested with Playwright), a visa-application backend.

## Stack

**Backend:** Node.js, Express, Fastify, TypeScript, Prisma, PostgreSQL, RabbitMQ, Docker
**Auth/Security:** JWT, Passport, rate-limiting, Joi/Zod validation
**Mobile:** Flutter, Riverpod
**Other:** Python, C# / .NET Core, Java, SOAP/S/MIME integrations, AWS S3, MongoDB, SQL Server, Firebase, Kubernetes, GCP

**Languages I can work in:** TypeScript/JavaScript, C#, Python, Dart, Java, SQL

## Contact

- 📫 Email: [yusufbozkurt2022@gmail.com](mailto:yusufbozkurt2022@gmail.com)
- 🌐 Site: [yusufbozkurt.com](https://yusufbozkurt.com)
- 💼 LinkedIn: [yusuf-b](https://www.linkedin.com/in/yusuf-b-7828351b2/)
- GitHub: [@softwareruless](https://github.com/softwareruless)
