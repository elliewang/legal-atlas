# Legal Atlas — Insurance Legal Operations

A responsive, standalone legal engagement and matter management **demo** for Wenting Wang. Free static hosting on GitHub Pages. No API keys, frameworks, or server required.

## Features

1. Legal request / engagement initiation — claims, operations, HR, compliance and litigation sources
2. Centralized intake — request title, facts, owner, jurisdiction, urgency and metadata
3. Triage and risk assessment — matter classification and manual risk grading
4. Matter creation and counsel assignment — internal or external counsel field
5. Legal execution — configurable action checklist and legal workstream guidance
6. Review and approval — review queues and governance guidance
7. Resolution and financial management — matter budget, spend, settlement control points
8. Closure and analytics — matter outcomes and department reporting
9. Customer communication — email drafts via `mailto:`, phone calls via `tel:`, texts via `sms:`
10. Atlas Assistant — local rule-based chatbot grounded in the stored matters, not an AI/LLM and not legal advice

Matters can be created, edited, deleted, filtered and searched. CSV and JSON export are supported. Responsive desktop/mobile UI.

## Publish on GitHub Pages

1. Create a public GitHub repository, e.g. `legal-atlas`.
2. Upload `index.html`, `styles.css`, `app.js`, `.nojekyll`, and this README to its repository root (not a nested folder).
3. Go to **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, `main`, `/(root)`, then Save.
5. Your site will be available at `https://YOUR_GITHUB_USERNAME.github.io/legal-atlas/` after deployment.

Or open `index.html` locally to try it.

## Important security and production limitations

- This is an **illustrative portfolio/demo**, not a production legal, claims, or customer communication system. Demo seed records are fictional.
- Matters and checklist tasks are stored only in the browser's **localStorage** and are not synced across devices. Clearing browser storage deletes them. Use **Export** to back up.
- **Do not enter real client, claimant, employee, attorney-client privileged, financial account, health, PII, or confidential case/evidence content**. GitHub Pages is public static hosting and localStorage is not appropriate for confidential regulated legal records.
- Document uploads, secure evidence vault, approval attestations, access controls, identity verification, audit trail, email/SMS delivery tracking, policy system integration, case encryption, litigation holds, litigation deadlines/calendar integrations and secure cloud storage are **not implemented**.
- The email/phone/SMS controls invoke the user's installed application; they do not send messages or perform calls themselves.
- The assistant is explicitly **rules-based**. It uses browser records and does not offer privileged legal advice, case forecasts or server-side AI.

Production deployment would require authenticated backend APIs, role-based access control, tenant isolation, legal hold/retention policies, encryption, monitored audit logging, secure document storage, a compliant messaging solution, data protection assessments, and counsel/compliance sign-off.

## Files

- `index.html`: semantic UI and application shells
- `styles.css`: responsive styling
- `app.js`: workspace logic, chatbot, records, views and exports
- `.nojekyll`: disable Jekyll processing for direct static publication
