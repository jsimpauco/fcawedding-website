# Wedding Website
Personal project as I ~~was voluntold~~ graciously wanted to help my sister and my new brother in law.
This project was initially built with a [React + TypeScript + Vite](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts)
template with ESLint, and is hosted on Cloudflare with a custom domain.

## Link
https://fcawedding.com/

## Table of Contents
- [Required packages](#required-packages)
- [Installation & Setup](#installation--setup)
- [Dev Mode](#dev-mode)
- [Deployment](#deployment)

### Required packages
- **Node.js**: `v22.x`
- **npm**: `v10.x`
  - Alternative package managers such as **pnpm** or **yarn** should work as well

### Installation & Setup
> [!NOTE]
> Ensure you are using the correct Node.js version before attempting to setup project.
1. Clone the repository
```
git clone https://github.com/jsimpauco/fcawedding-website.git
cd fcawedding-website
```
2. Install packages from `packages.json`
```
npm install
```

### Dev Mode
Using Vite's development mode, you can make changes to the project and by saving the file, see the changes in real time.
To start the local development server:
```
npm run dev
```
Click the link after running to open the localhost server.
> [!IMPORTANT]
> Ensure you save the file before looking at changes you have made.

### Deployment
Only the `main` branch is deployed to the Cloudflare hosted website.
Once a push is made to `main`, Cloudflare will automatically build and update the website.
> [!IMPORTANT]
> Ensure pushes are made to the correct branch to ensure full website functionality.