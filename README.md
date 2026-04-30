# 🎱 Snooker Club Management System

A complete, mobile‑friendly web app for managing a snooker/pool club.  
Supports **5 tables**, **game‑based pricing**, **snacks ordering**, **discounts (percentage or fixed)**, **unique receipt IDs**, **customer phone numbers**, **time extensions** (free for most games, charged for Century), **printable receipts**, **daily/all‑time Excel exports**, and a **password lock**.

🔒 **Password:** `WorkingToBetterMyself`

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔐 **Password protection** | Only authorized staff can access the system. |
| 🎯 **Game catalog** | Predefined games (1 Ball, 6 Ball, 10 Ball, Full Frame, Century, Half Century etc.) – each with price, duration, and “extension chargeable” flag. |
| ➕ **Add another game** | While a table is occupied, add more games to the same bill. |
| ⏱️ **Time tracking** | Real‑time countdown; “TIME UP!” notification when minutes reach zero. |
| 🍽️ **Snacks menu** | Editable list of snacks (Samosa, Soft Drink, Sheesha, Tea, Coffee, etc.). |
| 🏷️ **Discounts** | Apply a **percentage** (%) or a **fixed PKR amount** discount to any active session. |
| 🖨️ **Print receipt** | Print current bill without closing the table, or print final receipt when closing. |
| 🧾 **Unique receipt ID** | Format: `CUE-YYYYMMDD-XXXX` – automatically generated. |
| 📞 **Customer phone number** | Store phone number with each session; appears on receipt and in Excel exports. |
| 💰 **Revenue tracking** | Shows **Today’s Revenue** (sum of closed bills from current date) and **Pending Revenue** (active sessions). |
| 👁️ **Hide/Show revenue** | Toggle visibility of revenue cards. |
| 🗑️ **Reset revenue** | Clear all closed bill history (with confirmation). |
| 📊 **Excel export** | Export **daily** transactions or **all** transactions as CSV (opens in Excel/Sheets). |
| ⚙️ **Editable game prices** | Add new games or edit existing prices/durations/extensions flag. |
| 🍿 **Editable snacks menu** | Add, modify, or delete snack items. |
| 📱 **Mobile optimized** | Works on iPhone, iPad, Android – touch‑friendly buttons, responsive grid. |

---

## 🚀 How to Use

### 1. Open the app
- Save the HTML file as `index.html` (or any name) and open it in any modern browser (Chrome, Edge, Safari, Firefox).
- You will see a **password screen**.

### 2. Unlock with password
- Enter: `CodingToBetterMyself`  
  *(You can change this in the source code – search for `CORRECT_PASSWORD`)*

### 3. Start a game
- Click **Start Game** on any free table.
- Enter customer name (optional phone number).
- Choose a game (price and duration are shown).
- Click **Start Session** – the table becomes occupied and time starts counting down.

### 4. Manage an active session
- **Extend Time** – adds extra minutes (free for most games, charged for Century).
- **Add Game** – adds another game to the same bill (price + duration added).
- **Add Snack** – select quantity and add snack items.
- **Orders** – view detailed list of time charges and food items; remove unwanted snacks.
- **Print Bill** – print a receipt without closing the table.
- **Discount** – apply a percentage or fixed‑amount discount.
- **Close Bill** – finalises the bill, adds to revenue, prints receipt, and frees the table.

### 5. Manage settings
- **Games** button – edit existing game prices, durations, extension chargeable flag, or add a brand‑new game.
- **Snacks** button – edit the snacks menu (add, delete, change prices).
- **Hide / Show** – toggle revenue cards visibility.
- **Reset** – permanently delete all closed bills (active sessions remain).
- **Daily Report** – export today’s closed transactions as CSV.
- **All Report** – export every closed transaction ever as CSV.

---

## 🔧 Changing the Password

Open the HTML file in any text editor and search for:

```javascript
const CORRECT_PASSWORD = "CodingToBetterMyself";
