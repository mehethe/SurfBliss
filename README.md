# SurfBliss

The aim of this project was to create a robust business website utilizing Next.js as the frontend framework and Strapi as the headless CMS (Content Management System). The website features fully dynamic content management, including blogging and event management capabilities.

## Key Features:

### Next.js Frontend:
- Leveraged Next.js's server actions and SSR capabilities to improve page load performance and SEO, resulting in faster rendering times and enhanced discoverability.
- React components is used to create a modular and reusable UI for the website.
- Integrated React Suspense with fallback mechanism to improve loading transitions.

### Strapi CMS and Dynamic Content Management:
- Strapi serves as the backend CMS, providing a user-friendly interface for content creation, editing, and management, allowing administrators to easily update and publish new content without modifying the codebase.
- Custom content types are defined for various sections of the website, including blog posts, events, pages, etc.
- Strapi's REST API is leveraged to fetch data from the backend and populate the frontend dynamically.

### Blogging:
- A blogging section is integrated into the website, featuring articles, news, and updates relevant to the business or industry.
- Each blog post has a dedicated page with rich text content, images, metadata

### Event Management:
- An event management system is implemented to showcase upcoming events, camps, etc.
- Events are shown with detailed information including date, time, location, description, and registration option.

### Responsive Design and Dark mode:
- The website will be designed responsively to ensure optimal viewing and interaction experience across devices of all sizes, including desktops, tablets, and smartphones.
- Automatically detects the user's system theme preference (light or dark mode).
- Provides users with a manual toggle option to switch between light and dark modes regardless of the system theme.

## Tech Stack:
- **Frontend:** Next.js, React.js, Tailwind CSS, Zustand, Axios, React Toastify.
- **Backend:** Strapi, PostgreSQL.
- **Additional Services:** Cloudinary (for image storage).

## Live Demo:
- [https://surf-bliss.vercel.app/](https://surf-bliss.vercel.app/)
