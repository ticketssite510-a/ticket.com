# TTicket — Football Ticketing Website (starter prototype)

A responsive frontend prototype for a multi-match football ticket marketplace with a booking modal and demo admin panel.

## Included
- Match cards and search/filter
- Ticket categories and quantity
- Booking preview/reference (NOT a real ticket)
- Demo admin modal
- Responsive styling

## Run locally
Open `index.html` in a browser, or use a local static server.

## Deploy on Render (static site)
1. Push this folder to a GitHub repository named `tticket`.
2. Render → New → Static Site → connect the repository.
3. Build command: leave blank.
4. Publish directory: `.`
5. Deploy.

## Important before real sales
This is a frontend prototype, not production ticketing/payment software. It does not charge cards, verify payments, store orders, or issue valid tickets. Never represent demo bookings as paid tickets.

For live card payments, add a server-side checkout integration (e.g. Stripe Checkout or a locally supported gateway), webhook signature verification, database-backed orders, secure admin authentication, inventory/seat locking, refunds/cancellation rules, and QR tickets generated only after verified payment. Never put secret payment keys in frontend JavaScript. Confirm event organizer authorization and ticket inventory.
