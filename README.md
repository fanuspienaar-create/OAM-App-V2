# OAM Studio v29

Fixes:
- Restores the Quotes list renderer so Quotes & Invoices no longer throws `renderQuotes` ReferenceError.
- Quote deletion, closing and quote-to-invoice conversion remain available. Converted quotes stay saved.
- Adds reusable Units to item lines.
- Adds Manage Units in both Quote and Invoice item sections. Units can be added, edited, saved and deleted.
- Unit selection is stored with each line item without changing the approved PDF column layout.
- Service worker cache bumped to v29.
