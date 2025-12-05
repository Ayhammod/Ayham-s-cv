# Standalone Portfolio for GitHub Pages

This folder contains a standalone version of your portfolio website that is ready to be hosted on GitHub Pages.

## How to Deploy

1. **Profile Image**: 
   - Make sure you have your profile image named `profile.jpg` inside this `standalone` folder.
   - If your image has a different name, rename it to `profile.jpg` or update the `src` attribute in `index.html`.

2. **Upload to GitHub**:
   - You can upload the contents of this `standalone` folder to your GitHub repository.
   - If you want this to be your main site, upload these files to the root of your repository (replacing the Flask files).
   - Alternatively, you can keep them in a folder (like `docs`) and configure GitHub Pages to serve from that folder.

3. **Enable GitHub Pages**:
   - Go to your GitHub repository settings.
   - Go to "Pages" section.
   - Select the branch (usually `main` or `master`) and the folder where you uploaded these files.
   - Click Save.

## Features

- **No Flask Required**: These are pure HTML/CSS/JS files.
- **Embedded Resources**: All CSS and JavaScript are embedded directly into the HTML files, so you don't need to worry about linking external files.
- **Navigation**: Links are set up to navigate between the `.html` files.
- **Dark/Light Mode**: The theme toggle works and saves your preference.
