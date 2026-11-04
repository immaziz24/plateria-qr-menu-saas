# Plateria QR Menu SaaS — Initial Source Archive

This repository contains recovered restaurant-specific digital menu prototypes and the planning blueprint for the Plateria multi-restaurant QR menu platform.

## Repository contents

- `restaurant-demos/` — standalone HTML menu prototypes for Golpo Solpo, Payel Restaurant, and Akanto Apon Restaurant.
- `docs/Restaurant-QR-Menu-SaaS-Blueprint.pdf` — the original WordPress SaaS architecture and phased-development blueprint.
- `docs/SOURCE-INVENTORY.md` — scope, provenance, and implementation status notes.

## Important project status

**This is an initial source archive, not a completed or deployable SaaS application.** It does not currently include the central multi-tenant WordPress plugin/theme, tenant authentication and authorization, production database schema/migrations, owner/admin dashboards, kitchen display system, payment integrations, or deployment configuration.

The HTML files are restaurant-specific standalone prototypes. Review their restaurant details, contact data, menu prices, external image links, and WhatsApp destinations before deploying or handing them to a restaurant.

## Suggested next development phases

1. Audit and normalize the existing standalone menu pages.
2. Build the central multi-restaurant account and tenant model.
3. Implement restaurant profiles, menu/category/item management, and stable restaurant URLs.
4. Implement QR generation and tenant-safe public menu rendering.
5. Add ordering, kitchen workflow, billing, and integrations only after the first version is stable.
6. Add automated tests, security review, backup/restore, and deployment documentation.

## Security note

Do not commit production credentials, API keys, database passwords, private customer data, or live service-role secrets. Use environment-specific secret storage for future integrations.
