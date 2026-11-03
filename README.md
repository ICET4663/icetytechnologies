# Icety Technologies

Business website for **Icety Technologies**, a software development and technology solutions business in Nigeria.

**Live site:** https://icetytechnologies.netlify.app

## About the business

Icety Technologies designs, develops and deploys web applications, mobile applications and digital platforms for businesses and individuals. Services include custom software, payment gateway integration, API development, database management, application maintenance and technical consultancy, for clients in logistics, financial technology and e-commerce.

| | |
|---|---|
| Trading name | Icety Technologies |
| Country | Nigeria |
| Industry | Digital services |
| Category | Web development and programming |
| Contact | adetolaelemide@gmail.com |

## Pages

| Page | File | URL |
|---|---|---|
| Home (services, pricing, work, about, contact) | `index.html` | `/` |
| Terms of Service | `terms.html` | `/terms` |
| Privacy Policy | `privacy.html` | `/privacy` |
| Refund Policy | `refund.html` | `/refund` |
| Not found | `404.html` | any unknown path |

## Run locally

It is a plain static site with no build step:

```bash
python -m http.server 8080
```

Then open http://localhost:8080.

## Deploy

Hosted on Netlify. `netlify.toml` publishes the repository root and sets security headers. When the Netlify site is linked to this repository, every push to `main` deploys automatically.

## Editing

- **Prices:** the `#pricing` section in `index.html`
- **Contact details:** the `#contact` section and footer in `index.html`
- **Policies:** `terms.html`, `privacy.html`, `refund.html`
- **Styles:** `style.css`
