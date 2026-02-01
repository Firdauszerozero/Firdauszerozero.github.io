# Welcome to your Whosthees project

## Project info

**URL**: https://whosthees.dev/projects/REPLACE_WITH_PROJECT_ID

## How can I edit this code?

There are several ways of editing your application.

**Use Whosthees**

Simply visit the [Whosthees Project](https://whosthees.dev/projects/REPLACE_WITH_PROJECT_ID) and start prompting.

Changes made via Whosthees will be committed automatically to this repo.

**Use your preferred IDE**

Pushed changes will also be reflected in Whosthees.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

This project is configured for deployment to GitHub Pages.

1. Create a new repository on GitHub named `YOUR_USERNAME.github.io` (replace YOUR_USERNAME with your GitHub username).
2. Push this code to the `main` branch of that repository.
3. In your repository settings, go to Pages and set the source to "GitHub Actions".
4. Update the `homepage` in `package.json` with your GitHub username: `"homepage": "https://YOUR_USERNAME.github.io"`
5. Push the changes, and the GitHub Actions workflow will build and deploy the site.
6. The site will be live at `https://YOUR_USERNAME.github.io`

## Can I connect a custom domain to my Whosthees project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.whosthees.dev/features/custom-domain#custom-domain)
