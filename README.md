# Astro Project

This is an Astro JS project that includes a home page, gallery page, and contact page. 

## Project Structure

```
astro-project
├── public
│   └── favicon.ico
├── src
│   ├── components
│   │   └── Header.astro
│   ├── layouts
│   │   └── MainLayout.astro
│   ├── pages
│   │   ├── index.astro
│   │   ├── gallery.astro
│   │   └── contact.astro
├── package.json
├── astro.config.mjs
└── README.md
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd astro-project
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to `http://localhost:3000` to see the home page.

## Pages

- **Home Page**: Located at `/src/pages/index.astro`, this page welcomes users and provides an introduction to the project.
- **Gallery Page**: Located at `/src/pages/gallery.astro`, this page showcases a collection of images or artworks.
- **Contact Page**: Located at `/src/pages/contact.astro`, this page contains contact information and a form for inquiries.

## Components

- **Header Component**: Located at `/src/components/Header.astro`, this reusable component includes navigation links to the home, gallery, and contact pages.

## Layouts

- **Main Layout**: Located at `/src/layouts/MainLayout.astro`, this layout wraps around the page content and includes the Header component for consistent styling.

## Configuration

- **Astro Configuration**: The `astro.config.mjs` file contains project-specific settings and integrations.
- **Package Configuration**: The `package.json` file lists the project's dependencies and scripts.

## License

This project is licensed under the MIT License.