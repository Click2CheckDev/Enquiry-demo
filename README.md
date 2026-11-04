# Crystal Hub — demo

A clickable walkthrough of Crystal Specialist Finance's Property Finance Enquiry
run through the Click2Check hub, showing both the broker's side and the
customer's side:

1. **Enquiry form** – Crystal's front page, then their form with Click2Check's
   required customer details added, including the live hub's postcode lookup
   (Find → pick an address → OK; the demo uses an invented address list).
   "Fill with sample customer" types the demo customer in one field at a time.
   The broker fills in what only they know;
   answers the data will supply are shown as dashed boxes. The broker picks the
   checks (credit report, Open Banking) and who pays (the firm or the customer).
2. **Customer consent** – the customer's phone (simulated): text link, consent,
   payment if the customer is paying, identity check, choose a bank.
3. **AI fill** – Click2Check reads the credit report and bank data and fills the
   rest of Crystal's form, each answer marked with where it came from, and checks
   the broker's details against the credit file.
4. **Credit & Open Banking** – Click2Check's aggregated view (credit report and
   bank compared) plus each report in full.
5. **Documents** – credit report, Open Banking report, 3 months of bank
   statements, the aggregated view and the completed form: download as PDF or
   view as HTML.

It sits alongside the [HMRC demo](https://click2checkdev.github.io/HMRC-demo/)
and the [Affordability demo](https://click2checkdev.github.io/Affordability-demo/)
and uses the same hub styling.

**Live: https://click2checkdev.github.io/Crystal-demo/**

Fictional data, no backend: nothing is requested from any bureau or bank and
nothing is sent. One self-contained `index.html`; the PDFs are made in the browser.
