# 🔐 Simple Login/Signup System with HTML, CSS, JS, PHP & MySQL

A beginner-friendly authentication system created by **2GreekDevs**. This project provides a simple way to implement user registration and login using front-end technologies and PHP/MySQL for the backend.

> 💡 Perfect for learning or customizing into your own web projects.

---

## 🚀 Features

- ✅ User registration with username, email, and password
- 🔑 Secure login with password hashing
- 💾 MySQL database integration
- 📁 Clean and simple file structure
- 🧠 Easy to understand and modify

---

## 🧰 Tech Stack

- HTML5 / CSS3
- JavaScript (optional)
- PHP 7+
- MySQL (MariaDB)

---

## 🗃️ Database Setup

1. Create a database named `login_app`
2. Import the SQL file:

```sql
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL UNIQUE,
    email VARCHAR(100) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```
3. Update your db.php with your database credentials.

⚙️ How to Use
🔧 Local (using XAMPP/Laragon)

    Place all files in htdocs/your-folder/

    Start Apache & MySQL from your control panel

    Import the database via phpMyAdmin

    Visit http://localhost/your-folder/index.html

🌍 Online Hosting

    Use a PHP-supported host like:

        000Webhost

        InfinityFree

        Or any cPanel-based hosting

    Upload all files & import database.sql through phpMyAdmin

🔐 Security Notes

    Passwords are hashed using password_hash() for security

    For production, use HTTPS and prepared statements with PDO or MySQLi

    Add sessions and input validation for extra protection

📌 Customization Tips

    💬 Add email verification or password reset

    🎨 Improve the UI with a CSS framework (like Tailwind or Bootstrap)

    🔐 Add session handling and dashboard redirects

    ---

🤝 About Us

2GreekDevs is a Greek tech duo building creative digital tools, websites, Discord bots, and more.
Follow us for updates:
[📸 Instagram](https://www.instagram.com/2greekdevs/)
[🌐 Website](2greekdevs.com)
[💬 Discord Server](https://discord.gg/dHCvUaFAAH)

