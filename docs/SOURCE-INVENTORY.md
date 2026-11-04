# Source Inventory and Handover Notes

## Included source files

| Path | Description | Notes |
|---|---|---|
| `restaurant-demos/golpo-solpo-fixed-menu.html` | Golpo Solpo standalone menu page | Recovered HTML source; not runtime-tested in this upload. |
| `restaurant-demos/Payel-Restaurant-Premium-Digital-Menu.html` | Payel Restaurant standalone menu page | Recovered HTML source; check restaurant contact/menu data before deployment. |
| `restaurant-demos/Akanto-Apon-Restaurant-Luxury-Digital-Menu.html` | Akanto Apon standalone menu page | Recovered HTML source; not runtime-tested in this upload. |
| `docs/Restaurant-QR-Menu-SaaS-Blueprint.pdf` | Multi-restaurant QR Menu SaaS blueprint | Planning document; it is not executable application source. |

## Scope boundaries

The included HTML pages are separate restaurant menu prototypes. Their presence does not establish that the central multi-tenant SaaS, login, permissions, QR management, ordering backend, kitchen display, billing, or production database have been implemented.

## Excluded material

Other client menu revisions and Mughal E Raj restaurant management files were intentionally excluded to keep this repository dedicated to Plateria QR Menu SaaS. A separate potentially unrelated `taste_of_bengal_hostinger_fixed.html` file was also not included pending confirmation of its project ownership.

## Review status

- Source files recovered and copied into the repository package.
- No full browser/mobile regression test has been performed as part of this archive upload.
- External assets and services referenced by the HTML (for example remote images, fonts, maps, telephone links, and WhatsApp) may change or be unavailable.
- Run a secrets/configuration audit and test all order/reservation flows before production use.
- Verify actual tenant isolation and backend authorization once SaaS backend code is added.
