---


# 📘 Bookopus Main Site

Welcome to the main site for **Bookopus**, a platform built to organize, display, and manage books elegantly. This is the frontend web application, crafted in PHP, HTML, CSS, and JavaScript to deliver a fast, clean, and responsive user experience.

![Bookopus Screenshot](assets/screenshot.png)

---

## 🌐 Live Preview

Check out the live site: [https://bookopus.com](https://bookopus.com)  
No longer Active 

---

## 🛠️ Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Language     | PHP 8+             |
| Server       | Apache/Nginx       |
| Frontend     | HTML5, CSS3, JS    |
| Framework    | None (Vanilla PHP) |
| Version Control | Git + GitHub    |

---

## ✨ Features

- 📚 Homepage with curated book sections
- 🔍 Dynamic search bar and results view
- 📖 Category-based book browsing
- 📩 Contact form with validation
- 📱 Mobile-friendly responsive layout
- ⚡ Lightweight and fast-loading pages

---

## 🚀 Getting Started

### 📦 Prerequisites

Ensure your system has:

- PHP 8.0+
- Apache/Nginx Web Server
- MySQL or MariaDB (if database is used)
- Composer (optional, for dependency management)

### ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/vinayaksandilya/Bookopus-Main-Site.git

# Move into the project directory
cd Bookopus-Main-Site

# If composer.json is available
composer install
````

### 🔧 Server Setup

If you're using Apache:

```apacheconf
<VirtualHost *:80>
    ServerName bookopus.local
    DocumentRoot /path/to/Bookopus-Main-Site
    <Directory /path/to/Bookopus-Main-Site>
        AllowOverride All
        Require all granted
    </Directory>
</VirtualHost>
```

Enable the site and restart Apache:

```bash
sudo a2ensite bookopus.conf
sudo systemctl restart apache2
```

Or simply run via PHP's built-in server (for testing):

```bash
php -S localhost:8000
```

---

## 💡 Usage

* Browse the homepage to view featured book categories.
* Use the search functionality to filter books by name, author, or keyword.
* Navigate via the menu to other static or dynamic pages (like Contact or About).
* Customize sections from the PHP templates or static files.

---

## 📁 Folder Structure

```
Bookopus-Main-Site/
├── assets/          # CSS, JS, images
├── includes/        # PHP includes or components
├── pages/           # Page templates like contact.php, about.php
├── index.php        # Main entry point
└── .htaccess        # Apache config for routing (if used)
```

---

## 🧑‍💻 Contributing

Contributions, issues, and feature requests are welcome!
Please follow the standard GitHub workflow:

1. Fork the project
2. Create your branch: `git checkout -b feature/awesome-feature`
3. Commit changes: `git commit -m 'Add awesome feature'`
4. Push to the branch: `git push origin feature/awesome-feature`
5. Open a Pull Request

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 🙋‍♂️ Author & Contact

Made with ❤️ by **[Vinayak Sandilya](https://github.com/vinayaksandilya)**
📧 Email: [vinayaksandilya@gmail.com](mailto:vinayaksandilya@gmail.com)
🌐 Website: [https://bhoral.com](https://bhoral.com)

---

## 📌 Acknowledgments

* PHP.net documentation
* W3Schools and MDN for frontend references
* Inspiration from open-source book platforms



---

Let me know if you'd like me to auto-fill additional sections like dependencies, screenshot assets, or license text.
```
