# Hansi’s Children’s Day Challenge

A static, mobile-first seven-step surprise website for Hansi. It has playful name and height challenges, a final crown celebration, and a Happy Children’s Day message.

## Run locally

This project has no dependencies. Open `dist/index.html` in any web browser.

For a local web server (recommended), run this from the project folder:

```bash
npx serve dist
```

Then open the local URL shown in the terminal.

## Upload to GitHub

1. Create a new empty GitHub repository.
2. In this project folder, run:

```bash
git init
git add .
git commit -m "Add Hansi Children's Day challenge"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub details.

## Host on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
2. Select **Add New → Project** and import this GitHub repository.
3. Keep the detected settings and click **Deploy**.

`vercel.json` tells Vercel to publish the `dist` folder, so no build command is needed.
