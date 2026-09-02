RS Chatrabash Final PWA
========================
Primary member data: 37 members.

Rent:
- Postpaid system.
- January rent is collected in February, February in March, etc.
- December 2026 rent is collected in January 2027.
- Opening due is 0.
- Underpayment creates due that carries forward.
- Overpayment creates advance that carries forward.
- Rent history is available per member.

Deposit:
- Deposit is separate from monthly rent.
- Every member can have a manually entered deposit amount.
- When a member leaves, deposit can be used to settle the member's current rent due.
- Deposit settlement is recorded separately as "জামানত থেকে Rent Due সমন্বয়".
- Settlement cannot exceed the current rent due or remaining deposit.
- Remaining deposit can be recorded as refunded money.

WiFi:
- WiFi connection/monthly fee is separate from rent.
- WiFi payment, due and advance never merge with rent.

Member:
- Individual profile.
- Room, rent, phone, address, district, upazila, joining date, deposit and WiFi fee.
- Add new members.
- Mark members as left.

Data:
- Local storage.
- Backup and restore JSON.
- PWA/offline service worker.

Installation:
Upload index.html, app.js, manifest.json, sw.js, icon.svg, icon-192.png and icon-512.png to the GitHub Pages repository root.
