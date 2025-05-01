# Last-Mile-App
# 🛣️ Last-Mile Route Planning App

A Laravel-based web application to optimize and manage last-mile delivery routes from distribution centers to end customers. Designed to improve delivery efficiency, reduce costs, and streamline logistics.

---

## 🚀 Features

- 📍 Dynamic route planning based on delivery locations
- 📦 Delivery center and package management
- 🗺️ Google Maps integration for route visualization
- 📊 Real-time distance and duration calculation using APIs
- ✅ Delivery status tracking and history
- 🔐 Secure authentication and role-based access

---

## 🛠️ Tech Stack

- **Framework**: Laravel 10+
- **Frontend**: Blade, Tailwind CSS (optional)
- **Database**: MySQL / PostgreSQL
- **Maps & Routing**: Google Maps API or OpenStreetMap
- **Auth**: Laravel Breeze or Laravel Jetstream

---

## 📂 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/shivupurbay1922/last-mile-route-planner.git
   cd last-mile-route-planner

=>Install dependencies
composer install
npm install && npm run dev


=>Set up the environment
cp .env.example .env
php artisan key:generate

=>Configure .env

Set your DB credentials

Add your Google Maps API Key (if using)

=>Run migrations
php artisan migrate

=>Serve the app
php artisan serve




📌 Project Structure
app/Models: Eloquent Models for DeliveryCenters, Packages, Routes, etc.

app/Http/Controllers: Controllers for business logic

resources/views: Blade templates for UI

routes/web.php: Web routes

database/migrations: DB schema definitions


📈 Roadmap
 Create delivery center & route models

 Add map integration for routes

 Implement drag-and-drop route reordering

 Add analytics dashboard

 Mobile-friendly UI



 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.







