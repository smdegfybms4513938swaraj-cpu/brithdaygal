# Happy 20th Birthday, Bubboo! 🎉

A personalized, interactive, and romantic birthday web application built with React, Vite, Tailwind CSS, and Framer Motion. 

This project was created as a special digital gift, featuring interactive elements like a virtual letter, a masonry photo dump, a "Reasons I Love You" section, and a retro-style arcade randomizer game.

## Features

- **Interactive Envelope & Letter:** A beautifully animated letter that opens up to reveal a personalized message.
- **Moments (Photo Dump):** A responsive masonry grid showcasing favorite memories and photos.
- **Reasons I Love You:** A stylized, masonry-layout collection of sweet and funny reasons.
- **Bubboo's Arcade:** A retro-themed interactive arcade machine!
  - Drag-and-drop coin insertion.
  - Interactive joystick.
  - Randomized humorous challenges and inside jokes.
  - Confetti celebrations.
- **Dark Mode Support:** Fully responsive and adapts to both light and dark themes.

## Tech Stack

- **Frontend Framework:** [React 19](https://react.dev/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations:** [Motion (Framer Motion)](https://motion.dev/) & [GSAP](https://gsap.com/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Effects:** `canvas-confetti`

## Getting Started

To run this project locally on your machine, follow these steps:

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed (v18 or higher recommended).

### Installation

1. Clone the repository:
   ```bash
   git clone <your-github-repo-url>
   cd <your-repo-directory>
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

### Running the Development Server

Start the local development server:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:3000` (or the port specified in your terminal) to view the app.

### Building for Production

To create a production-ready build:

```bash
npm run build
```

The compiled assets will be generated in the `dist` folder, which you can then deploy to any static hosting service like Vercel, Netlify, or GitHub Pages.

## Deployment

Since this is a Vite-based static site, you can easily deploy it for free using:
- **Vercel:** Just import your GitHub repository.
- **Netlify:** Connect your GitHub repo and set the build command to `npm run build` and publish directory to `dist`.
- **GitHub Pages:** Use the `gh-pages` package or GitHub Actions to deploy the `dist` folder.

## License

This project is for personal use.
