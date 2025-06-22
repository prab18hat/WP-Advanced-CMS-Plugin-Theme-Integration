# WP-Advanced CMS Plugin & Theme Integration 🧩

A custom WordPress theme developed from scratch alongside a fully functional custom plugin to manage dynamic content sections. This project demonstrates proficiency in WordPress theme hierarchy, PHP templating, plugin development, WooCommerce integration basics, and core CMS architecture using WordPress.

---

## 🔧 Project Features

### 🖌️ Custom WordPress Theme
- Built fully from scratch using **PHP, HTML, CSS, and Bootstrap**
- Implements complete **WordPress theme hierarchy**:
  - `index.php`, `single.php`, `page.php`, `header.php`, `footer.php`, `sidebar.php`
- Responsive mobile-first layout with Bootstrap
- Dynamic post rendering using the **WordPress loop**
- Featured images, pagination, and sidebar widget support
- Theme metadata included via `style.css`

### ⚙️ Custom WordPress Plugin
- Adds a custom dashboard section for CMS block toggling
- Implements dynamic post sections via **shortcodes**
- Integrates with theme using conditional visibility toggles
- Admin options page to control block appearance and layout
- Secure, modular structure using WordPress plugin development standards

### 🛠️ Technical Stack

| Technology | Role |
|------------|------|
| **WordPress** | CMS platform |
| **PHP** | Theme and plugin logic |
| **MySQL** | Database for posts, options, and content |
| **HTML5 & CSS3** | Page structure and styling |
| **Bootstrap 5** | Responsive design |
| **JavaScript** | DOM interactions |
| **Git** | Version control |

---

## 📦 Plugins Used

- **Custom CMS Plugin (Built from scratch)** – to create flexible admin sections  
- **Classic Editor** (optional) – for easier post formatting  
- **WooCommerce** (optional) – for e-commerce extensions in future

---

## 📁 File Structure (Theme Only)


---

## 🧪 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/wp-advanced-cms-theme.git
Copy the theme folder to:

swift
Copy
Edit
/xampp/htdocs/wordpress/wp-content/themes/
If plugin is separate:
Copy the plugin folder to:

bash
Copy
Edit
/wp-content/plugins/
Start Apache & MySQL (using XAMPP or LocalWP)

Go to http://localhost/wordpress/wp-admin

Activate the theme and plugin via Dashboard → Appearance → Themes / Plugins

Go to Pages → Add new shortcodes like:

csharp
Copy
Edit
[custom_cms_block]
Check your home/front page for layout

🧠 What I Learned
Building custom WordPress themes using template hierarchy

Working with WP hooks and filters

Creating shortcodes and plugin menus in the admin panel

Using Bootstrap for responsive design inside WordPress

Managing content using PHP + MySQL dynamically

Creating custom options pages in WP dashboard

📜 License
This project is open-source and free to use under the MIT License.

📩 Contact
Made with 💻 by Prabhat Mishra
