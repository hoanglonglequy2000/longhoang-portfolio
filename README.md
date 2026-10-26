# Long Hoang Portfolio — static Vercel package

This package is based on the uploaded Chrome-saved HTML file.

## Deploy
1. Push the files to a GitHub repository.
2. Import the repository at https://vercel.com/new.
3. Framework Preset: **Other**. No build command. Output Directory: `.`.
4. Click Deploy.

## Important limitations
- Only the saved homepage HTML was provided. Other portfolio pages are not included.
- The browser-saved companion folder `longhoang's portfolio_files/` was not provided, so its Framer `script_main.B6T-lhLC.mjs` bundle is missing. Framer-powered interactions may fail, even though static content can render.
- Saved image `src` references were switched to the matching public Framer image URLs. Images, styles/fonts and other modules remain dependent on Framer servers and the internet.
- This is a deployable static snapshot, not original Framer source code. It has not been end-to-end verified live on Vercel.

For full interactive fidelity, also supply the companion `_files` folder or export the complete original project.
