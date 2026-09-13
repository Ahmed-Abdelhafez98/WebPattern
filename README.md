# WebPattern — Web Technologies Blog with Admin Panel

WebPattern is a blog / CMS where registered users write posts about web technologies. An admin panel lets moderators approve posts and comments before they go live.

## Features

- Public blog: posts by category, per-author pages, full-text search
- User registration and login
- Comments on posts, held for moderation
- Admin panel: manage posts, categories, comments, users and profile

## Stack

PHP (procedural, no framework) · MySQL · Bootstrap (LTR + RTL) · Font Awesome

## Run locally

1. Create a MySQL database and import your schema.
2. Set the connection in `includes/db.php`.
3. Serve the folder with Apache/PHP (e.g. XAMPP) or:

```bash
php -S localhost:8080
```

Blog at `http://localhost:8080`, admin panel at `http://localhost:8080/admin`.
