# ♻️ REVIVE - Modern Second-Hand Fashion Marketplace

**REVIVE** is a modern, sustainable peer-to-peer (P2P) fashion marketplace designed for users to buy, sell, and exchange pre-owned clothing, footwear, bags, watches, and accessories. 

The platform's primary goal is to promote **sustainable fashion** by encouraging the reuse of quality products, reducing textile waste, and making premium fashion more affordable and accessible to everyone.

---

## 🎯 Problem Statement & Objective
The fast fashion industry contributes significantly to global textile waste and environmental pollution. **REVIVE** aims to solve this problem by creating a circular economy where users can easily extend the lifecycle of fashion items. 

Our objective is to provide a seamless, secure, and user-friendly platform where individuals can monetize their unused wardrobe and buyers can access high-quality fashion at discounted prices.

---

## 🚀 Core Features & Modules

### 1. User & Authentication Module
*   **Secure Registration & Login:** Email-based registration with secure password hashing.
*   **OTP Verification:** Integration with PHPMailer to send OTPs for password recovery and account verification, ensuring top-tier security.
*   **Profile Management:** Users can update their personal details and track their activity.

### 2. Seller Module
*   **Product Listing Pipeline:** Sellers can upload images, set prices, write descriptions, and categorize items (e.g., Clothing, Watches, Footwear).
*   **Seller Dashboard:** A dedicated interface to manage active listings, track total products, and monitor sales.

### 3. Buyer Module
*   **Dynamic Shop/Catalog:** A fully responsive product grid featuring search and category filters.
*   **Product Details:** Detailed product view with descriptions, seller info, and high-quality images.
*   **Wishlist:** Buyers can save their favorite items for future consideration.
*   **Checkout System:** Integrated checkout flow for smooth transactions.

### 4. Communication Module
*   **Real-Time Chat System:** A dedicated `chat.php` interface allowing direct P2P communication between buyers and sellers for negotiation and queries.

### 5. Admin Panel & Moderation
*   **Admin Dashboard:** Centralized control for administrators to oversee platform operations.
*   **User & Product Management:** Admins can view, approve, or ban users, and monitor active product listings.
*   **Reporting:** Admins can generate PDF reports for platform analytics.

### 6. Sustainability Tracking (Unique Feature)
*   **Impact Badges:** User profiles display personalized environmental impact metrics, such as "Water Saved" or "Waste Reduced", rewarding users for their participation in the circular economy.

---

## 🛠️ Technology Stack

| Component | Technology Used |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Custom Styling), JavaScript |
| **Backend** | PHP (Core PHP/Procedural) |
| **Database** | MySQL (Relational Database Management) |
| **Email Service** | PHPMailer (For OTP and notifications) |
| **Architecture** | Client-Server Architecture |
| **Server** | XAMPP (Apache HTTP Server) |

---

## 📂 Project Structure

```
revive/
│
├── actions/                  # Backend PHP logic (Login, Registration, OTP, Product handling)
├── assets/                   # Static assets (Images, CSS stylesheets, JavaScript files)
├── config/                   # Configuration files (Database connection - db.php)
├── includes/                 # Reusable UI components (Navbar, Footer, Sidebar)
│
├── admin_dashboard.php       # Admin control center
├── chat.php                  # P2P Messaging interface
├── checkout.php              # Payment and order processing
├── index.php                 # Landing page
├── login.php / register.php  # Authentication pages
├── product_details.php       # Detailed view of a single product
├── seller_dashboard.php      # Seller management interface
├── shop.php                  # Main product catalog
└── verify_otp.php            # Security verification page
```

---

## ⚙️ Installation & Setup Guide (For Viva/Testing)

To run this project locally on your machine, follow these steps:

1. **Install XAMPP:** Download and install XAMPP for Windows/Mac/Linux.
2. **Start Servers:** Open the XAMPP Control Panel and start the **Apache** and **MySQL** modules.
3. **Clone the Repository:** 
   * Navigate to your XAMPP `htdocs` directory (e.g., `C:\xampp\htdocs\`).
   * Clone this repository or extract the project folder here. Make sure the folder is named `revive`.
4. **Database Configuration:**
   * Open your browser and go to `http://localhost/phpmyadmin`.
   * Create a new database named `revive_db` (or as specified in your `config/db.php`).
   * Import the provided `.sql` file (if included) to set up the tables automatically.
5. **Run the Project:**
   * Open your browser and type: `http://localhost/revive/`
   * You should see the Revive landing page!

---

## 🎓 Academic Project Details

*   **Project Name:** Revive - Second-Hand Fashion Marketplace
*   **Degree:** Bachelor of Computer Applications (BCA) - Final Year Project
*   **Developer:** Prince Raj (Reg. No: BCA-310-23093)
*   **Institution:** CIMAGE College
*   **GitHub Username:** BCA-310-23093-PrinceRaj
