# Faktury

An invoice maker for a Czech sole trader (OSVČ) who is not a VAT payer (neplátce DPH). It looks like a kraft time card on a dark desk, the same style as Work Days.

The whole app is one file, `index.html`. Open it in a browser or serve it with GitHub Pages.

## What it does

- Edit the invoice on the card itself: client, dates, a subject line, and lines with a date, venue or description and price.
- Bring in worked days from Work Days. In Work Days, open the ⋯ menu, pick a month and choose "Download for Faktury". Then use "Import from Work days" here, or drop the file on the card. Days and extra hours are priced with the day rate and extra-hour rate set under Your details.
- Show a QR Platba payment code once your bank account is entered.
- Make a PDF in Czech, on kraft or white paper. Long invoices continue onto a second page.
- Keep a list of invoices with paid, due and overdue status, plus this year's total against the 2 000 000 Kč VAT registration limit.

Every invoice says "Dodavatel není plátcem DPH." and "Fyzická osoba zapsaná v živnostenském rejstříku."

## Home screen

Opened from GitHub Pages, the app can go on your home screen: on iPhone use Share › Add to Home Screen, in Chrome use Install app. The icon is a stencil F under a yellow highlighter on the dark desk.

## Where data is kept

Inside Claude, invoices and your details are saved to your Claude account. Opened anywhere else, including GitHub Pages, they are saved in that browser only.
