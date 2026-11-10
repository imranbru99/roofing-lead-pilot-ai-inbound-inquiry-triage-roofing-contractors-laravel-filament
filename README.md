# RoofingLeadPilot — AI Inbound Inquiry Triage CRM for Roofing Contractors (Laravel Filament)

**RoofingLeadPilot** is a modular Laravel + Filament SaaS that helps roofing contractors classify website, phone, and email inquiries into qualified CRM opportunities, then operate on service requests, field technicians, and job tickets — with AI assist, human approval, and full audit logging.

## SEO / Niche Keywords

roofing contractor CRM, inbound inquiry triage, AI lead classification, roofing sales operations, service request management, field technician dispatch, job tickets roofing, storm damage emergency triage, roof leak intake, full reroof quotes, shingle repair leads, flat roof TPO EPDM, metal roof standing seam, gutter fascia soffit jobs, insurance roof inspection claims, skylight vent flashing, Jobber alternative intake, ServiceTitan lead routing, QuickBooks customer handoff, Google Calendar dispatch, TCPA messaging consent, licensed roofer technician operations software, home & field services automation, Laravel Filament SaaS, modular AI business automation, USA roofing contractors 2026

### Related keyword tags
`roofing-contractors` `inbound-inquiry-triage` `ai-lead-scoring` `crm-opportunities` `service-requests` `field-technicians` `job-tickets` `sales-operations` `home-field-services` `laravel` `filament` `docker` `saas` `ai-automation` `human-approval-workflow` `audit-log` `messaging-consent` `storm-damage` `roof-leak` `full-reroof` `shingle-repair` `flat-roof` `metal-roof` `insurance-inspection` `jobber` `servicetitan` `quickbooks` `google-calendar`

## Problem solved

For roofing contractors: classify website, phone and email inquiries and create qualified CRM opportunities; operate on service requests, field technicians and job tickets.

- **Target buyer:** Roofing Contractors owner / operations lead  
- **Workflow:** Inbound Inquiry Triage  
- **Function:** Sales operations  
- **MVP:** 1 intake trigger → draft/action → human approval → audit log  
- **Pricing hypothesis:** Pilot $199–$799/mo  
- **Risk/compliance:** MED — messaging consent, licensing and safety  

## Features & modules

All modules are toggleable in Filament → **Feature Modules** (or `config/modules.php` defaults).

### Core (ON by default)
- Inbound Inquiry Triage  
- AI Classification (`roofing-triage-v1`: storm damage emergency, roof leak, full reroof, shingle repair, flat roof, gutter/fascia, metal roof, insurance inspection, skylight/vent, maintenance)  
- Human Approval Workflow  
- CRM Opportunities  
- Service Requests  
- Field Technicians  
- Job Tickets  
- Audit Log  
- Messaging Consent  
- Follow-Up Drafts  
- Universal Slug Engine  
- AI Hub Provider Switch (local equivalent)  
- Drutogoti Speed Layer (local equivalent)  
- Admin Panel Extras (local equivalent)  

### Optional / niche (OFF by default)
- Customer Portal  
- Attendance Hub (local `laravel-attendance-hub` equivalent)  
- Unicode PDF Exports (local `laravel-unicode-pdf` equivalent)  
- AI Catalog / Lead Scrape (local `laravel-ai-catalog` equivalent)  
- Jobber / ServiceTitan / QuickBooks / Google Calendar integrations  
- Multi-Location  

> Packagist packages under `imrandevbd/*` were not installable at build time (stability/availability). Equivalent local services ship in `app/Services/` and are documented here.

## Multi-type demo users

Password for all: **`password`**

| Role | Email |
|------|-------|
| Admin | admin@roofingleadpilot.test |
| Owner | owner@roofingleadpilot.test |
| Staff | staff@roofingleadpilot.test |
| Technician | tech@roofingleadpilot.test |
| Customer (no Filament) | customer@roofingleadpilot.test |

Admin panel: [http://localhost:8133/admin](http://localhost:8133/admin)

## Public marketing pages

- `/` Home — brand + product story  
- `/features` All capabilities  
- `/modules` Every module ON/OFF  
- `/workflow` MVP triage flow  
- `/pricing` Pilot pricing  
- `/demo` Live intake form + credentials  
- `/contact` Hire / contact  

## Docker run

```bash
docker compose up -d --build
```

App URL: **http://localhost:8133**

Services:
- `app` → host **8133**
- `mysql` → host **33096**

First boot runs migrations, seeds demo data, and publishes Filament assets.

Stop:

```bash
docker compose down
```

## Tech stack

- PHP 8.3+ / Laravel 13  
- Filament 4 admin  
- MySQL 8.4 (Docker; database-backed cache/session/queue)  
- Modular feature flags (`ModuleSetting` + `ModuleManager`)  
- Heuristic AI triage engine (`AiTriageService`) with approval workflow  
- Docker Compose  

## Screenshots

See `docs/screenshots/`:
- `home.png` — marketing home  
- `features.png` — features page  
- `admin-login.png` — Filament admin login / panel entry  

## Contact / Hire
- Developer: Imran Ahmed (IMRAN Dev BD)
- Website: https://imrandev.bd/contact
- Email: me@imrandev.bd
- GitHub: https://github.com/imranbru99
