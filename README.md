# Agiones CMS -- Community / Server Directory Platform

A lightweight, modern and feature-rich CMS built for gaming communities,
server lists, and content hubs. Designed for fast shared hosting,
powered by pure PHP, and flexible enough to let you rename core modules
like **Community → Server** or **Blog → News** depending on your project
needs.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![PHP Version](https://img.shields.io/badge/php-%3E%3D7.4-8892BF.svg)
![MySQL](https://img.shields.io/badge/mysql-%3E%3D5.7-4479A1.svg)

## ✨ Features

### Core

-   Community/Server Directory with profiles, tags, and customizable
    labels\
-   Voting system with 48-hour cooldown\
-   Comment system with moderation\
-   News/Blog module with SCEditor + BBCode\
-   Custom pages (About, Contact, FAQ)\
-   User roles: User / Moderator / Admin

### Admin Panel

-   Dashboard with stats & pending submissions\
-   Manage servers, news/blog posts, comments, users\
-   JSON Theme Manager\
-   SEO tools (OpenGraph, Twitter, Schema)\
-   Display limits, approval rules, visibility controls\
-   Module renaming options

### Advanced

-   Moderator permissions\
-   Google OAuth login\
-   Custom HTML injection\
-   Featured servers\
-   Hashtag management\
-   Responsive layout

## 🎨 Themes

-   JSON-based themes (theme.json + style.css + script.js)\
-   CSS variables\
-   Included theme: Deep Ocean

## 🔐 Security

-   CSRF protection\
-   Sanitization & escaping\
-   PDO prepared statements\
-   bcrypt password hashing\
-   Role-based access control\
-   IP banning

## 🔎 SEO

-   Meta tags\
-   OpenGraph & Twitter Cards\
-   Schema.org support\
-   Canonical & hreflang\
-   Sitemap\
-   Robots admin protection

## 📦 Requirements

-   PHP 7.4+\
-   MySQL 5.7+ / MariaDB 10.2+\
-   Apache + mod_rewrite\
-   PDO MySQL\
-   Optional: Google OAuth

## 🚀 Installation

1.  Upload project\
2.  Create MySQL database\
3.  Import database.sql\
4.  Configure config.php\
5.  (Optional) Google OAuth\
6.  Create first admin\
7.  Access /admin

## 👥 User Roles

### User

-   Manage own servers\
-   Create news/blog posts\
-   Vote and comment

### Moderator

-   Approve/remove servers, posts, comments\
-   Create news/blog posts\
-   Cannot change system settings

### Admin

-   Full access\
-   Manage users, themes, SEO, system

## 📜 License

MIT License

## 📞 Support

Open an issue on GitHub.

---

<div align="center">

**If you find this plugin useful, please give it a ⭐ on GitHub!**

Made with ❤️ by [Yamiru](https://yamiru.com)

</div>
