# Nike Landing Page

A modern, responsive Nike landing page built with React and Tailwind CSS. This project showcases a clean UI, interactive product displays, and a mobile-friendly design.

[View live demo](https://nike-iota-sepia.vercel.app/)

## Features

- **Hero Section:** Eye-catching introduction with dynamic shoe image selection.
- **Popular Products:** Grid display of featured Nike shoes.
- **Super Quality:** Highlight of product quality and craftsmanship.
- **Services:** Cards for shipping, payment, and support services.
- **Special Offer:** Promotional section with call-to-action buttons.
- **Customer Reviews:** Testimonials from satisfied customers.
- **Newsletter Subscribe:** Email input for updates and newsletters.
- **Footer:** Company info, navigation links, and social media icons.
- **Responsive Design:** Looks great on all devices.

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [ESLint](https://eslint.org/) & [Prettier](https://prettier.io/) for code quality

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/dafriyie7/Nike_Landing_Page.git
   cd nike-2-0
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Start the development server:**

   ```sh
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```sh
npm run build
```

### Preview Production Build

```sh
npm run preview
```

## Project Structure

```
nike-2-0/
├── public/                # Static assets
├── src/
│   ├── assets/            # Images and icons
│   ├── components/        # Reusable UI components
│   ├── constants/         # Static data (products, reviews, etc.)
│   ├── sections/          # Page sections (Hero, Footer, etc.)
│   ├── App.jsx            # Main app component
│   ├── main.jsx           # Entry point
│   └── index.css          # Tailwind and global styles
├── index.html
├── tailwind.config.js
├── vite.config.js
└── package.json
```

## Customization

- **Colors, fonts, and breakpoints** are configured in [`tailwind.config.js`](tailwind.config.js).
- **Images and icons** are in [`src/assets/images`](src/assets/images) and [`src/assets/icons`](src/assets/icons).
- **Section content** can be edited in [`src/sections`](src/sections).
- **Product, service, and review data** are in [`src/constants/index.js`](src/constants/index.js).

## License

This project is for educational/demo purposes.

---

Inspired by Nike's branding and modern
