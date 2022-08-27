# SvelteKit `router = false` bug

1. `npm install`
2. `npm run dev`
3. Open the website in the browser
4. Click `Go to page two`
5. Click the browser back button

The URL changes to `/`, but the page content doesn't change to `/`.
