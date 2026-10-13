# Alejandro Cabrera

I got into this as a kid, swapping the hard drive of the family laptop and installing Mandriva just to play Wormux. These days I build websites, backends and automations from Granollers, near Barcelona. Most of it goes through **Digital DesAny**, the studio I run with Oriol Tamborero.

<img src="https://skillicons.dev/icons?i=go,java,spring,nextjs,ts,postgres,redis,docker,cloudflare,vercel,wordpress,linux&perline=12" alt="Go, Java, Spring, Next.js, TypeScript, PostgreSQL, Redis, Docker, Cloudflare, Vercel, WordPress, Linux" />

---

## <img src="https://www.digitaldesany.com/logo/logo-facetedmonogram-aurora.svg" height="24" alt="" /> Digital DesAny

Small businesses around here usually come to us with one of these:

- a website they're a bit embarrassed to send to customers
- a task someone does by hand every week that a script could do
- a tool that doesn't fit the way they actually work

That's what we fix. Websites, automations (with AI when it helps, plain rules when it doesn't), custom software, and social media for the ones who'd rather not deal with it. In Catalan or Spanish, in person around Granollers and Barcelona or remotely.

Oriol leads sales and social media. I build, and I also handle pricing, the servers and a good share of the client calls.

| Project | What we did |
| --- | --- |
| [Lara's Oak](https://www.digitaldesany.com/es/casos-exito/lara-oak) | Portfolio for a storyboard and concept artist, with a CMS built on our own block system |
| [Paula Krebel](https://www.digitaldesany.com/es/casos-exito/paula-krebel) | Trilingual portfolio for a children's illustrator, plus her brand and a design system |
| [Roses de Sant Jordi](https://www.digitaldesany.com/es/casos-exito/rosesstjordi) | Digital roses with a dedication for Sant Jordi. Over 500 sent, and it trended on Reddit Catalunya |
| Hidrotech Bordalló | Social media for an industrial cleaning machinery company: demo reels, LinkedIn, YouTube, customer emails |

Once a project is paid, the code and the design belong to the client, with full documentation. If they ever want to move to someone else, they can do it without starting from zero.

**How we run it.** Client sites on Next.js and Vercel, Cloudflare for DNS and email. Whatever shouldn't be serverless lives on our own VPS: n8n for the automations, invoicing, internal tools, and an OpenAI-compatible gateway in front of the models our automations use.

**On my desk right now**

- Self-hosted contract signing, so clients can sign a proposal from a link
- Invoicing plugins that fit the way we actually bill
- A monthly report on how visible a business is in AI answers, tested on ourselves first

> [!TIP]
> Got a business in Catalonia and something stuck on your website or in your day-to-day? Write to **info@digitaldesany.com**. We'll tell you where to start, and if you don't need us, we'll tell you that too.

---

## Before

**VMV Cosmetic Group** · 2025-2026
Lead web developer for a cosmetics group: 30+ domains, 21 live sites, and a fair amount of Go and Java glue behind them.

<details>
<summary>What I built there</summary>

- A WAF in Go with IP reputation scoring
- A Java 21 / Spring Boot service that exposes the IBM i (AS/400) ERP as a REST API
- A biometric e-signature platform in Next.js
- An internal AI gateway with an OpenAI-compatible API
- WhatsApp Business notifications for the regional branches, in Go

</details>

**Neibr** · co-founder
When a parcel delivery failed, instead of going back to the sender it went to a neighbour within 200 m. I wrote the backend and also took care of deployment, the website and part of the sales. It won one of the Santander X Spain Awards 2026 at UVic. We still closed it in 2026, before launch: talking to a big carrier showed us problems in the model that code wasn't going to fix.

<details>
<summary>Technical bits</summary>

- Go (Fiber), PostgreSQL, Redis
- Assignment: SQL bounding-box prefilter, then exact Haversine distance
- Multi-tenant API keys, idempotent writes, HMAC-signed webhooks, append-only audit ledger
- Last load test: ~2.9M requests in 50 minutes (~968 req/s), p95 under 100 ms, zero 5xx

</details>

**Earlier**

- Cashless payments for vending machines at Automated Transactions: translating payment payloads to hex and talking to the machine over a 9600-baud serial bus (MDB).
- DAW degree. Final project: [Peer2Stream](https://github.com/Alexasto12/peer2stream), a site to discover and track movies and series, built with Ismael Delgado (10/10).
- Before all that, years of fixing family and neighbours' computers. That's how I paid for my first PC.

**Off the clock** I self-host more than is reasonable at home: a local AI stack, a modded Minecraft server, and whatever I'm taking apart that week.

---

[digitaldesany.com](https://www.digitaldesany.com/es) · [Digital DesAny on LinkedIn](https://www.linkedin.com/company/digital-desany/) · [dev.alexasto.com](https://dev.alexasto.com) · [LinkedIn](https://www.linkedin.com/in/ccalejandro/)

<sub>Fet a Granollers.</sub>
