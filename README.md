# rayensalem.github.io

Personal site of Rayen Salem, SOC analyst and incident responder. Live at https://rayensalem.github.io

It is a single self-contained page: `index.html` holds the markup, styles and script, with all the text in one CONTENT block near the top of the script, in English and French. `og.png` is the preview image shown when the link is shared.

To add the CV, upload `Rayen_Salem_CV.pdf` next to `index.html`. The page shows the CV links only when that file is present.

Tickets from the contact form and the console are emailed through [FormSubmit](https://formsubmit.co), a free form-to-email relay, so the site needs no server. The very first ticket makes FormSubmit send a one-time "Activate Form" email to the contact address; after one click there, tickets arrive in that inbox with the visitor's address as Reply-To. FormSubmit then also sends a random alias for the address: putting it in `relayId` in the PROFILE block keeps the address itself out of the page's requests.
