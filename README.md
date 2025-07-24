# 💰 PriceDrop Detection

**PriceDrop Detection** is a simple and powerful web application that helps users track the price of their desired products online. Users can set a target price, and once the product's price drops to or below this target, they will receive alerts via **Email** and **WhatsApp**. The app also includes **User Authentication** for personalized tracking and notification management.

---

## 🚀 Features

- 🔗 Add product URLs you want to track
- 🎯 Set your target price
- 🔐 User Authentication (Login/Register)
- 📧 Email notifications when price drops
- 💬 WhatsApp integration for instant alerts
- 🕒 Periodic price checking (via cron or scheduler)

---

## 📸 Demo

_Include screenshots or a video here if you have them._

---

## 🔧 Technologies Used

- **Backend:** Node.js 
- **Frontend:** React / HTML / CSS / (your UI framework)
- **Database:**  PostgreSQL (whichever you're using)
- **Authentication:**  JWT
- **Email Service:** Nodemailer 
- **WhatsApp Integration:** Twilio WhatsApp API
- **Web Scraping / Price Monitoring:** Puppeteer 

---

## 🛠️ How It Works

1. **User Signup/Login:**  
   Users create an account to manage and track their product watchlist.

2. **Add Product to Watchlist:**  
   Users paste the product link and set a target price.

3. **Price Checker:**  
   A scheduled job (cron) scrapes the product page and checks the current price at regular intervals.

4. **Notification System:**  
   - If the current price is equal to or lower than the target price:
     - Send an email to the user.
     - Send a WhatsApp message to their registered number.

5. **Dashboard:**  
   Displays a list of all tracked products, their current prices, and notification status.

---

## 🧪 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/pricedrop-detection.git
   cd pricedrop-detection
