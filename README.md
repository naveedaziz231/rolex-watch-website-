# 👑 ROLEX Luxury Watch Website (Supabase Backend)

Ek ultra-luxury **Rolex Watch Website** jise **HTML5, CSS3, JavaScript** aur **Supabase Backend** ke sath complete build kiya gaya hai. Isme Rolex signature **Emerald Green & Sapphire Blue luxury gradients**, gold typography, dynamic product catalog, live search & category filters, watch detail modal, aur product & price management ke liye **Admin Dashboard** shamil hai.

---

## 📁 Folders & Files Structure

```text
rolex watch website/
│
├── index.html              # Main Luxury Rolex Website (Showcase, Gallery, Modals, VIP Concierge)
├── admin.html              # Admin Portal (Products aur Prices add/edit/delete karne ke liye)
├── schema.sql              # Supabase Database Table Schema & Policies (SQL code)
├── README.md               # Complete Urdu & English Guide
│
├── css/
│   ├── style.css           # Luxury Theme (Emerald Green & Sapphire Blue Gradients, Glassmorphism)
│   └── admin.css           # Admin Dashboard Styling
│
└── js/
    ├── supabase-config.js  # Supabase Client Configuration (Aapki API Keys se configured)
    ├── app.js              # Client Frontend Logic (Dynamic Fetching, Search, Filters, Bag)
    └── admin.js            # Admin Logic (Realtime Supabase Insert, Update, Delete)
```

---

## ⚡ Supabase Setup (Sirf 1 Simple Step)

Aapka Supabase project already `js/supabase-config.js` me connect kar diya gaya hai:
* **Project URL:** `https://iqszzwqwmunkskbgbzzr.supabase.co`
* **Anon Key:** Configured

### Table Banane Ka Tareeqa:
1. Apne [Supabase Dashboard](https://supabase.com/dashboard) me jayein.
2. Apne project `iqszzwqwmunkskbgbzzr` ko open karein.
3. Left menu se **SQL Editor** par click karein.
4. `schema.sql` file ke saare code ko copy karke wahan paste karein aur **"Run"** dabayein.
5. `watches` aur `inquiries` tables automatically create ho jayein gi!

---

## 🛍️ Products Aur Unki Prices Kaise Add Karein?

Aapne farmaya tha ke products aap khud add karein ge. Iske liye humne ek dedicated **Admin Portal (`admin.html`)** banaya hai:

1. Browser me `admin.html` ko open karein (ya website ke top navbar me **"Admin Portal"** button dabayein).
2. Form me watch ki details enter karein:
   - **Watch Name** (e.g. *Rolex Submariner Date*)
   - **Model** (e.g. *Oystersteel & Cerachrom*)
   - **Reference Number** (e.g. *126610LN*)
   - **Category** (*Professional, Classic, Submariner, Daytona, etc.*)
   - **Price & Currency** (e.g. *10,250 USD* ya PKR)
   - **Image URL** (Aap direct URL daal sakte hain ya Quick Presets par click karein)
   - **Specifications** (Dial, Case Material, Bracelet, Movement, Description)
3. **"Save Watch to Supabase"** par click karein.
4. Watch foran Supabase database me save ho kar live website (`index.html`) par luxurious presentation ke sath show hona shuru ho jayegi!

---

## 🎨 Features & Design Highlights

* **Rolex Emerald Green & Sapphire Blue Luxury Gradients:** Premium visual experience with glassmorphism and subtle lighting glows.
* **Dynamic Supabase Synchronization:** Har product aur price direct Supabase se realtime fetch hoti hai.
* **Instant Filtering & Live Search:** Categories (Professional, Classic, etc.) aur realtime search bar.
* **High-Definition Quick View Modal:** Watch ki complete specifications (Movement, Case, Bracelet, Ref #) view karne ke liye.
* **Inquiry Bag & VIP Concierge:** VIP purchases aur inquiry form jo inquiries ko record karta hai.
* **100% Responsive:** Mobile, tablet, laptop, aur ultra-wide screens par perfect layout.
