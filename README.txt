Bhaskar's Moving Sale Website

Files included
- index.html
- styles.css
- script.js
- items.js
- items_editable.csv
- photos/ folder

How to edit later
The website reads from items.js.

Each item is listed as a small block of text like:
{
  "id": 1,
  "name": "LG OLED TV - 65 inch",
  "category": "Electronics",
  "price": 650,
  "status": "Available",
  "notes": "No known burn-in.",
  "photo1": "photos/tv.jpg"
}

You can edit:
- name
- category
- price
- status
- notes
- photo1
- room/location

How to add photos
1. Put images into the photos folder
2. In items.js, set photo1 to something like:
   photos/my_item.jpg

How to mark an item sold
Change:
- Available
to:
- Pending
or:
- Sold

How to host
Upload all files to GitHub Pages, Netlify, Vercel, or any standard web host.
Make sure index.html stays in the main folder.

Important
items_editable.csv is there to help you review or edit in Excel.
The live website itself reads items.js, not the CSV.
