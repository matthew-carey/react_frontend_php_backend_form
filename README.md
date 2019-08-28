# react_frontend_php_backend_form
Basic form built in React with Google reCaptcha v2. Submits to PHP backend via AJAX.

## Installation
1. Clone repo
2. Install dependencies with `npm i`
3. Update `$sendTo` in [public/mailer.php](public/mailer.php) for your recipient email address.
4. Update `homepage` in [package.json](package.json) for your site path.
5. Update `sitekey` in [src/contact-page.js](src/contact-page.js) with your reCaptcha v2 sitekey.
6. Prepare your files for deployment via `npm run build`
7. Deploy the files in your newly created "build" directory.
