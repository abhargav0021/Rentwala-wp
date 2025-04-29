# Rentwala wp

Rentwala is a secure and user-friendly rental platform designed to connect product owners and renters. It was developed as a full-stack project for the Secure E-Commerce course.

🌐 **Live Site**: [https://rentwala.42web.io](https://rentwala.42web.io)

---

## 📸 Screenshots

### 🔹 Homepage
![Homepage](screenshots/homepage.png)

### 🔹 Product Listings
![Product Listings](screenshots/listings.png)

### 🔹 Login & Register
![Login](screenshots/login.png)

---

## ✨ Features

- 🛒 Rent & Post Products
- 🔐 Secure Login/Register System (PHP + MySQL)
- 🧑‍💼 Admin Dashboard for Managing Users and Products
- 💬 Contact & Feedback Forms
- 🔍 Search & Filter Capabilities
- 📁 Hosted on a Free PHP Hosting (InfinityFree)

---

## 🛠 Tech Stack

| Layer         | Technologies                          |
|---------------|----------------------------------------|
| Frontend      | HTML, CSS, JavaScript                  |
| Backend       | PHP                                    |
| Database      | MySQL                                  |
| Hosting       | InfinityFree (42web.io)                |
| Tools Used    | phpMyAdmin, XAMPP/WAMP, cPanel (for upload) |

---

## 🗃 Folder Structure
📁 rentwala/ │ ├── 📁 admin/ # Admin dashboard files ├── 📁 css/ # Stylesheets ├── 📁 includes/ # DB config and helper PHP files ├── 📁 js/ # Scripts ├── 📁 images/ # Assets & uploads ├── 📄 index.php # Homepage ├── 📄 login.php # Login page ├── 📄 register.php # Registration ├── 📄 contact.php # Contact form └── ... # Other core pages


---

## ⚙️ How to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/rentwala.git
   cd rentwala

$db_host = 'localhost';
$db_user = 'root';
$db_pass = '';
$db_name = 'rentwala';

Deployment via cPanel or InfinityFree
Compress your project into a .zip file.

Login to InfinityFree/cPanel → Go to File Manager.

Upload your .zip to htdocs/ → Extract it.

Create MySQL Database via MySQL Wizard.

Import the .sql file through phpMyAdmin.

Update /includes/config.php with new DB details.

✅ Site should be live at yourdomain.42web.io

