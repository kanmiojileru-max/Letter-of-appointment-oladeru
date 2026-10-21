CCC IJESHATEDO PARISH IV - INTERACTIVE LETTER OF APPOINTMENT (Diaspora Chairman)

CONTENTS
- index.html ........ the letter on the parish letterhead, green-and-gold animated
                      envelope, parish stamp (everything is built into this one file)
- generator.html .... creates personalised links for many recipients at once
- vercel.json ....... Vercel settings (clean URLs, no search indexing)

FEATURES
- Envelope addressed to the recipient, opens with an animation; stamp "presses" onto the letter
- Justified, properly aligned text; letterhead repeats on every printed page (A4-style, 2 pages)
- Accept Appointment: the recipient types their name and ticks to confirm; the acceptance is
  shown on the letter (and in the printed PDF) and can be sent to the Parish by email or WhatsApp
- Print / Save as PDF, Share, Copy link, text size (A- / A+) for easier reading
- Personalised links: name, reference number and date change; the letter wording does not
- Bulk link generator with Copy, WhatsApp and CSV download

DEPLOY ON VERCEL
1. Unzip, then in Vercel choose Add New > Project and upload the folder
   (or push it to GitHub and import it). Framework Preset: "Other".
   Leave Build Command and Output Directory empty.
2. Deploy and open the .vercel.app link.

PERSONALISED LINKS
  https://YOUR-SITE.vercel.app/?name=Mrs.%20Adeyemi&ref=CCC%2FIJP4%2F001&date=1%20November%202026
Or open https://YOUR-SITE.vercel.app/generator and paste a list of names.
The plain link shows the default recipient (Evang. Tokunbo) and the date set in index.html.

EDITING DEFAULTS
At the top of the script in index.html, change the CONFIG block: default name, letter date,
optional reference number and the Parish email used for acceptance and contact links.

NOTES
- Acceptance is saved on the recipient's own device. It is not sent automatically: the
  recipient uses the "Send by email / WhatsApp" buttons to notify the Parish.
- To print: choose "Save as PDF" and tick "Background graphics".
- Anyone with your site address can open /generator. Delete generator.html when finished if you prefer.
