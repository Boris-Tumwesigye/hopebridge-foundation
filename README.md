# Hopebridge Health & Education Foundation — News Website

This is a free, mobile-friendly static website starter. It includes:
- Responsive homepage
- Health, Education, Community and Opportunities categories
- Search and category filters
- Read-article popups
- Contact section and email form that opens the visitor's email app
- WhatsApp contact button (configure the number before publishing)

## 1. Personalise the website before publishing

Open `index.html` in a text editor and find this section near the bottom:

```js
const SITE_EMAIL = "info@hopebridgehealthandeducation.org";
const WHATSAPP_NUMBER = "211923381390";
```

The email and WhatsApp number have been filled in using the details you supplied. I interpreted your email as `info@hopebridgehealthandeducation.org`; please verify that this is the exact address. The WhatsApp number is configured as `211923381390`.

Also update the contact copy, mission statement, and footer if needed. The starter articles are examples, not live news. Replace them with fact-checked stories before promoting the site.

## 2. Free publishing with GitHub Pages

You need a free GitHub account and internet access.

1. Go to https://github.com and create/sign in to a free account.
2. Create a new repository named `hopebridge-news` (Public is simplest for free GitHub Pages).
3. Upload `index.html` to the repository's top level. You can upload the README too.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/ (root)`, then save.
7. Wait a few minutes and revisit **Settings → Pages** for the published website address. It will look similar to `https://YOUR-USERNAME.github.io/hopebridge-news/`.
8. Open the address on your phone and test the menu, article filters, contact email and WhatsApp button.

GitHub's interface can change; follow its current Pages prompts if labels differ.

## 3. Updating news

This starter is a static website, so articles are edited inside `index.html` in the `articles` array. To publish a story:
1. Make a backup copy of `index.html`.
2. Find `const articles = [` and duplicate an article object.
3. Give the new story a unique `id`, choose a category, update `title`, `summary`, `date`, `body` and `icon`.
4. Save and upload the updated `index.html` to GitHub, replacing the old one. GitHub Pages republishes it automatically.

For more frequent publishing without editing code, a later upgrade could add a free CMS. A real newsroom with logins, roles, image uploads and comments requires additional setup.

## 4. Important launch checklist

- Replace all placeholder contact details.
- Confirm the organisation's approved name, mission and legal status before making claims about registration.
- Replace demo articles with verified, dated stories and link to reliable sources.
- Do not publish private medical information or identifiable stories/photos of children without proper consent and safeguards.
- Add an editorial corrections/contact process.
- Test the site on mobile and check every link.
- GitHub Pages hosting is free for eligible public repositories. A custom domain is optional and normally costs money.

## Files

- `index.html` — the website
- `README.md` — these setup and publishing instructions
