# Chai Solutions website

A static website outlining the Chai Solutions organization and what they do, as
well as the products they offer.

Proudly built with [Astro](https://astro.build).

## Running

This is an Astro project managed with `npm`; use Node 20 or higher.

A [Nix](https://nixos.org) devshell and [`direnv`](https://direnv.net) script is
provided for convenience.

1. `npm install` :: install all dependencies and tools
2. `npm run dev` :: run server in development mode, at `http://localhost:4321`

## Deployment

Deployment is done using Netlify. Any updates to the `main` branch will
automatically trigger deployment of the static site to the domain
https://chai-solutions.netlify.app.

To test the deployed site, run `npm run build`. This builds a production version
of this website and outputs it to the `dist/` directory. Then, run
`npm run preview` to run the production server in preview mode.
