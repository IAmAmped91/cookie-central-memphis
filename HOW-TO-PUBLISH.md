# Cookie Central Memphis — Website

Hey Terrell, here's a quick guide to publishing Gina's site.

## What's in this folder

- **index.html** — the website itself (the whole site is one file)
- **images/** — all the photos used on the site

That's it. Just two things.

## How to put it online (free)

The easiest free option is **Netlify Drop**:

1. Go to **https://app.netlify.com/drop** in your browser
2. Drag the whole **cookie-central-memphis** folder onto the page
3. Wait a few seconds — it gives you a free link like `cookie-central-memphis-xyz.netlify.app`
4. Send that link to Gina, share on Facebook, put on her market signs

No account needed for the trial. To keep it forever (free) and get a custom address, sign up for a free Netlify account.

## How to use your own domain (like cookiecentralmemphis.com)

1. Buy a domain at **Cloudflare** ($10/year, cheapest) or **Namecheap**
2. In your Netlify dashboard, click "Domain settings" and add the domain
3. Netlify shows you what to change at your domain registrar
4. Takes a few minutes to connect

Total cost to run this site: **$10/year** for the domain. Hosting is free forever.

## How orders work

When someone fills out the form, an email gets sent to **gmcneil18@yahoo.com**. Gina replies directly with confirmation, total, and pickup details (including the home address if they chose home pickup).

The mailto form works but it opens the customer's email app. If you want a fancier form that goes straight to Gina without opening their email, that's a paid upgrade (~$0-9/month with Netlify Forms — first 100 submissions/month are free).

## Editing the site later

Just open **index.html** in any text editor (TextEdit, VS Code, whatever). Search for the text you want to change, save the file, drag the folder back to Netlify Drop. Done.

To update prices: search for `$24`, `$45`, `$10`, `$5`, `$8` and edit.
To update the market info: search for `Agricenter` and edit.
To add new photos: drop them in the `images/` folder and add a new gallery item in the HTML.

## Things you might want to add later

- Phone number (right now it's email only)
- Online payment (Square or Stripe)
- A real online order form that doesn't use mailto
- A newsletter signup
- Facebook/Instagram links
- A page for testimonials/reviews
- Holiday menu specials

All of these can be added to the same file — just let me know when you're ready.
