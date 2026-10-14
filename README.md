# Yaswanth Pemmadi — Animated Portfolio

## Run locally

```bash
npm install
npm run dev
```

## Contact form setup

The contact form is preconfigured to send submissions to **yaswanthp1156@gmail.com** using FormSubmit's AJAX endpoint. No environment variable or form ID is needed.

**First-time activation:** On the first form submission, FormSubmit may send an activation/confirmation email to the destination inbox. Open that email and confirm the address. After activation, visitor submissions are emailed to the inbox. Check Spam/Junk if the activation email is not visible. Until the service is activated, visitors can use the direct email link shown on the Contact page.

The form collects visitor name, work email, company (optional), subject, and message. Never collect passwords or sensitive personal information in this form.

## Deploy to Vercel

Import the project folder into Vercel or connect the Git repository, then deploy. No `VITE_FORMSPREE_ENDPOINT` variable is required for the contact form.

## Notes

- Built with React, Vite, React Router, Framer Motion and regular CSS.
- Project URLs are configured in `src/data/projects.js`.
- Replace any placeholder social profile links in `src/App.jsx` with the correct profile URLs before publishing.


## Contact links
The contact form has been replaced with direct links for LinkedIn, WhatsApp, phone, and email. WhatsApp/call/email use the contact number and email from the supplied resume. The LinkedIn button currently opens LinkedIn generally because a personal profile URL was not provided; replace the `linkedin` constant in `src/App.jsx` with your profile URL.
