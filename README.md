# TiRKiO Theme

TiRKiO is a modern general-purpose Jekyll theme designed for showcasing github pages. This repository provides the files necessary to set up and deploy the TiRKiO theme using GitHub Pages, with or without a custom domain.

## Features
- Modern responsive design using Bootstrap 5
- Pagination, sidebar, and category-based navigation
- Support for featured posts
- Integrated Disqus comments
- SEO-friendly with Jekyll plugins
- Customizable for your own neobanking or blog site
- A clean theme with no additional style definitions to Bootstrap, ensuring a lightweight and consistent design.

---

## Setup Instructions

### 1. Clone the Repository
Run the following command to clone the repository to your local machine:

```bash
git clone https://github.com/username/tirkio.git
cd tirkio
```

### 2. Customize the Theme
Modify the following files to personalize the theme:

- `_config.yml`: Update the site title, base URL, and other global settings.
- `pages/`: Add or update static pages like `about`, `ads`, or `privacy-policy`.
- `_posts/`: Add new blog posts in Markdown format.
- `_includes/` and `_layouts/`: Adjust templates and layouts if necessary.

---

## Deploying to GitHub Pages

### Option 1: Without a Custom Domain
1. Commit your changes to the `main` branch (or `gh-pages` branch if preferred):

    ```bash
    git add .
    git commit -m "Initial commit"
    git push origin main
    ```

2. Go to your repository settings on GitHub.
3. Under **Pages**, select `main` (or `gh-pages`) as the source and save.
4. Your site will be available at `https://<username>.github.io/<repository-name>/`.

### Option 2: With a Custom Domain
1. Update the `CNAME` file in the root directory with your custom domain name:

    ```
    www.example.com
    ```

2. In your DNS settings, add a CNAME record pointing your domain to `username.github.io`.
3. Follow steps 1–4 from Option 1.
4. Your site will now be accessible at your custom domain.

---

## Folder Structure
The directory structure of the TiRKiO theme is organized as follows:

```
├── _config.yml       # Site configuration file
├── _includes/        # Reusable HTML components (e.g., navigation, sidebar)
├── _layouts/         # HTML layouts for pages and posts
├── _posts/           # Markdown files for blog posts
├── _site/            # Generated static files (ignored in version control)
├── assets/           # Images, CSS, and JavaScript files
│   ├── css/          # Stylesheets
│   ├── images/       # Image assets
│   └── js/           # JavaScript files
├── pages/            # Static pages like About, Privacy Policy, etc.
├── Gemfile           # Ruby gem dependencies
├── CNAME             # Custom domain configuration (optional)
└── README.md         # Documentation for the theme
```

### Key Directories
- **`_config.yml`**: Contains site-wide configuration settings.
- **`_includes/`**: Includes reusable components like navigation, sidebar, and footer.
- **`_layouts/`**: Templates for different types of pages (e.g., posts, default layout).
- **`_posts/`**: Blog posts written in Markdown, following the naming convention `YYYY-MM-DD-title.md`.
- **`assets/`**: Contains CSS, JavaScript, and image files used in the theme.
- **`pages/`**: Stores static pages, such as About and Privacy Policy, in Markdown or HTML format.

---

## Contributing
Contributions are welcome! If you find issues or have suggestions for improvement, feel free to submit a pull request or open an issue.

---

## License
This project is open source and available under the [MIT License](LICENSE).

---

## Acknowledgments
- Bootstrap 5 Quartz for the frontend framework
- Jekyll for the static site generator
- Freepik for illustrations used in the theme
