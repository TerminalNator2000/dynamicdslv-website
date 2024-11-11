**dynamicdslv-website** is the official website for **Dynamic Data Solutions LV**, developed using **SvelteKit** and managed with **pnpm**. The site is designed for efficient performance and scalability, showcasing the company’s services, team, and contact information.

## Tech Stack

- **SvelteKit**: A modern framework that compiles to optimized JavaScript, offering faster load times and minimal runtime overhead.
- **pnpm**: A fast, efficient package manager that saves disk space and increases installation speed compared to npm.

## Project Structure

```plaintext
dynamicdslv-website/
├── src/
│   ├── lib/
│   │   ├── components/      # Reusable components (Header, Footer, Navbar, etc.)
│   │   ├── pages/           # Individual pages (AboutUs, Services, Team, ContactUs)
│   │   └── styles/          # Global and component-specific styles
│   ├── routes/              # SvelteKit routes (index, about, services, team, contact)
│   ├── app.html             # Base HTML template
│   └── app.css              # Global styles
├── static/                  # Static assets (favicon, logo)
├── .gitignore               # Git ignore file
├── LICENSE                  # MIT License
├── package.json             # Project dependencies and scripts
├── pnpm-lock.yaml           # Lock file for exact package versions
├── README.md                # Project documentation
└── svelte.config.js         # SvelteKit configuration
```

## Features

- **Modular Components**: The site’s sections, including Navbar, Header, and Footer, are built as reusable components.
- **Efficient Styling**: Styles are organized into global and component-specific files for clean, maintainable code.
- **Optimized Package Management**: Utilizes `pnpm` for faster, disk-efficient dependency management.

## Getting Started

### Prerequisites

- **Node.js** (version >= 16.0)
- **pnpm** (install globally using `npm install -g pnpm`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/dynamicdslv-website.git
   cd dynamicdslv-website
   ```

2. Install dependencies with pnpm:

   ```bash
   pnpm install
   ```

3. Start the development server:

   ```bash
   pnpm dev
   ```

4. Open [localhost:3000](http://localhost:3000) in your browser to view the website.

### Build for Production

To create an optimized production build, run:

```bash
pnpm build
```

## Why SvelteKit & pnpm?

### Benefits of SvelteKit over React

- **Faster Performance**: SvelteKit compiles to optimized JavaScript, providing faster load times than React’s virtual DOM approach.
- **Developer-Friendly**: SvelteKit’s reactivity is built-in, reducing the need for complex state management.
- **Built-in SSR**: Server-side rendering is supported out of the box for better SEO and initial load performance.

### Benefits of pnpm over npm

- **Faster Installations**: pnpm installs packages faster than npm, thanks to its unique symlink structure.
- **Reduced Disk Usage**: By storing dependencies globally, pnpm avoids duplications and saves space.
- **Monorepo-Friendly**: pnpm is optimized for monorepos, making it ideal for projects with multiple packages or services.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

