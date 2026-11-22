# ATHAR — Interactive Volunteer & Impact Platform

A responsive, interactive front-end prototype for the ATHAR entrepreneurship project.

## Features

### Volunteer experience
- Responsive discovery page with search and filters for location, cause and schedule
- Opportunity detail modal with organization, activity, skills and logistics
- Save/unsave opportunities
- Volunteer profile stored locally in the browser
- Submit applications and review application status

### NGO workspace
- Publish new opportunities through a guided form
- Review opportunities, capacity and application counts
- Update applicant statuses (Received, Shortlisted, Confirmed, Declined)

### CSR & project content
- Impact and CSR concept dashboard
- Project overview and customer-discovery evidence summary
- Volunteer and NGO Value Proposition Canvas
- Business Model Canvas overview
- Assumptions and next-step framing represented in the project material

## Run locally

No build tools or dependencies are required.

1. Download and extract the repository.
2. Open `index.html` in a modern browser.

Optional local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. GitHub Pages will provide a public URL.

## Project structure

```text
ATHAR-Interactive/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── css/
    │   └── styles.css
    └── js/
        └── app.js
```

## Important prototype boundaries

- This is a front-end demonstration. It does not have a live backend or database.
- Profile details, saved opportunities, new listings and applications are stored in the browser's localStorage on that device.
- No real email, SMS or push notifications are sent.
- NGO profile verification is represented as a visual sample only.
- Impact metrics are illustrative; no completed impact is claimed.
- NGO subscription prices are proposed concepts from the project material, not validated market prices.
- The matching is currently based on search and filters, not a production recommendation algorithm.
- The prototype uses sample organizations and opportunities; it is not connected to those organizations.

Before production, implement a secure backend, authentication and role permissions, database, NGO verification workflow, privacy and consent controls, real notification integrations, and security testing.

## Evidence note

The project summary and canvases reflect the ATHAR Group 6 material supplied in this conversation. The discovery summary refers to eight completed interviews (six volunteers, one NGO Operations Director and one Corporate CSR Manager). Findings are separated from assumptions; the prototype itself does not prove product adoption, impact outcomes or willingness to pay.

## License

No license is included. Add one only after the project owners decide how the work may be reused.
