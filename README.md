# 🏠 FindUrProperty

> **A clean, fully client-side real estate marketplace** — browse, list, and enquire about properties. No backend. No database. Just one HTML file.

🔗 **Live Demo → [findurprop.netlify.app](https://findurprop.netlify.app)**

---

## ✨ Features

### 👤 Role-Based Login
- Sign in as a **Buyer / Renter** or a **Seller / Agent**
- Different experience per role — buyers browse & enquire, sellers post & manage listings
- Role badge displayed in the navbar after login

### 🔥 Featured Properties (Homepage)
- Top 4 listings shown on the public homepage — visible before login
- Clicking a listing prompts login if not authenticated
- After login, opens the full property detail page

### 🏘️ Browse by Property Type
- Filter listings by **Villa**, **Apartment**, **House**, or **Condo**
- Clickable type chips inside the listings view
- Chips sync with the results grid instantly

### 📋 Post a Property *(Sellers only)*
- Fill in title, type, price, city, locality, beds, baths, area, amenities & description
- **Upload a photo** directly from your device — previewed before publishing
- Listing goes live instantly at the top of the grid

### 📄 Full-Page Property Detail
- Clicking any listing opens a **dedicated detail page** (not a modal)
- Large hero image, two-column layout — description on the left, price + contact card on the right
- Amenity tags, bedroom/bathroom/area breakdown
- **Send Enquiry** button visible to logged-in buyers only
- "← Back to listings" to return without losing scroll position

### 🔍 Search & Filter
- Search by city, locality, or property title
- Filter by **For Sale** / **For Rent** tabs
- Budget filter (Under ₹30L / ₹30L–₹80L / Above ₹80L)

---

## 🗂️ Project Structure

```
FindUrProperty/
└── index.html      # Entire app — HTML + CSS + JS in one file
```

Zero dependencies. Zero build step. Zero backend.

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/FindUrProperty.git

# Open in browser
open index.html
```

Or just drag `index.html` into any browser — it works instantly.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | Vanilla CSS |
| Logic | Vanilla JavaScript (ES6+) |
| Images | Base64 embedded (no external CDN) |
| Hosting | Netlify |

---

## 📸 Screenshots

| Homepage | Listings | Property Detail |
|----------|----------|-----------------|
| Hero with featured properties | Browse by type, search & filter | Full-page detail with contact card |

---

## 🧭 How It Works

```
Landing Page
    │
    ├─ Not logged in → See hero, stats, featured listings (locked)
    │
    └─ Login modal → Pick role (Buyer / Seller)
            │
            ├─ Buyer → Browse all listings → Click → Full detail page → Send Enquiry
            │
            └─ Seller → Browse + "+ Post Property" button → Upload photo → Publish
```

---

## 📝 Demo Credentials

No real auth — just enter **any name, email, and password** and pick a role. Data resets on page refresh (in-memory only).

---

## 📄 License

MIT — free to use, modify, and deploy.

---
