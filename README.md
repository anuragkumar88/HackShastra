
# 🏠 Student Accommodation Finder

A responsive web application built with **HTML, CSS, and JavaScript** that helps students and professionals find **PGs, Flats, and Hostels** across **Delhi, Chennai, and Bengaluru**.  

Users can search by **budget, city, and accommodation type**, view property details, save favorites, and contact owners directly via WhatsApp.

---

## 🚀 Features

- 🔎 **Search & Filter**  
  - Filter by **city, budget, and accommodation type** (PG / Hostel / Flat).  
  - Displays only relevant results.  

- 🏷️ **Accommodation Types**  
  - Paying Guest (PG)  
  - Flats / Apartments  
  - Hostels  

- ❤️ **Favorites**  
  - Save listings using the ❤️ button.  
  - Stored in browser **localStorage**.  

- 🖼️ **Photos & Logos**  
  - Each listing shows a **property photo** and a **logo icon** (PG/Flat/Hostel).  
  - “View Photos” button opens the property photo in a **Bootstrap modal popup**.  

- 📊 **Details Shown**  
  - Rent per month  
  - Travel time (approx)  
  - Safety score badge  
  - Ratings  
  - Verified / Suspicious badge  
  - AI recommendation text  

- 💬 **Contact Owners**  
  - One-click WhatsApp integration with pre-filled inquiry message.  

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap 5  
- **Logic:** Vanilla JavaScript (ES6)  
- **Icons:** Bootstrap Icons + Flaticon logos  
- **Images:** Unsplash (free stock photos)  
- **Storage:** LocalStorage (for favorites)  

---

## 📂 Project Structure

```
.
├── index.html       # Main UI
├── styles.css       # Custom styling
├── app.js           # Core logic (search, filters, favorites, modal)
├── assets/          # (optional) for storing images/icons if downloaded
└── README.md        # Documentation
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/accommodation-finder.git
   cd accommodation-finder
   ```

2. **Open `index.html` in your browser**  
   No backend is required (pure frontend project).

3. (Optional) Serve with a local dev server:
   ```bash
   npx live-server
   ```

---

## 🏙️ Cities Covered

- 🏠 **Delhi** (PGs, Hostels, Flats)  
- 🏠 **Chennai** (PGs, Hostels, Flats)  
- 🏠 **Bengaluru** (PGs, Hostels, Flats)  

Total: **12 demo listings** with different accommodation types and price ranges.

---

## 🚧 Future Improvements

- Add **multiple photos per listing** (image carousel).  
- Integrate **backend (Node.js / Express + MongoDB)**.  
- Allow owners to **post and manage their own listings**.  
- Optional: integrate **Google Maps for location-based search**.  

---

