# My Portfolio Website

Hey! This is my personal portfolio website where I showcase my work as a Software Development Engineer. I built it using React and Vite because I wanted something fast and modern.

## What's Inside

This site has everything you'd want to know about me professionally:
- A home section with a quick intro
- About me page with my background and skills
- My work experience and timeline
- Projects I've worked on (with links to repos and live demos)
- Contact form if you want to reach out
- Downloadable resume

## Tech I Used

- React 18 for the UI
- Vite for super fast dev experience
- React Icons for the icons
- Just good old CSS for styling (no frameworks needed!)
- Google Fonts (Inter and Poppins)

## Running Locally

Want to see how this works? Here's how to get it running:

```bash
# Install everything
npm install

# Start the dev server
npm run dev
```

Then open `http://localhost:5173` in your browser.

## Building for Production

```bash
npm run build
```

This creates a `dist` folder with all the optimized files ready to deploy.

## Deployment

I've set this up to deploy to GitHub Pages. Just run:

```bash
npm run deploy
```

And it'll build and publish everything automatically!

You could also deploy this to Netlify or Vercel - they both work great with Vite projects.

## Structure

Pretty straightforward setup:
- All components are in `src/components/`
- Each component has its own CSS file
- Resume PDF is in the `public` folder
- Main styles are in `src/index.css`

## Notes

The contact form currently just shows a success message. I'll hook it up to a backend service later (probably EmailJS or something similar).

If you're looking at this and want to use it as a template for your own portfolio, feel free! Just swap out my info with yours.

---

Built with React and Vite • 2025
