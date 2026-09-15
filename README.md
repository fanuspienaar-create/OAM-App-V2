# OAM Studio v30

Fixes:
- Restores the Quotes list renderer so Quotes & Invoices no longer throws `renderQuotes` ReferenceError.
- Quote deletion, closing and quote-to-invoice conversion remain available. Converted quotes stay saved.
- Adds reusable Units to item lines.
- Adds Manage Units in both Quote and Invoice item sections. Units can be added, edited, saved and deleted.
- Unit selection is stored with each line item without changing the approved PDF column layout.
- Service worker cache bumped to v29.

## v30 specific changes
- Invoice numbers now start at INV-0001 and increment sequentially from existing INV-#### records.
- Removed the Unit selector from quote/invoice item lines; users can describe duration/type in Description.
- Removed the now-unused Manage Units button from the item editor.
- All other v29 functionality and approved templates remain unchanged.


## v31 specific change
- Home page top logo and sidebar logo are fixed to the packaged original OAM Studio logo (`assets/oam-logo.png`).
- The uploaded Fanus Pienaar branding artwork remains reserved for Quote/Invoice PDF branding and is no longer assigned to the app chrome.
- No other v30 functionality or approved template was changed.
