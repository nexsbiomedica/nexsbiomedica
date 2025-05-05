# NEXS BioMedica Website

This package contains a complete deployable version of the NEXS BioMedica website.

## Deployment Instructions

### Option 1: Deploy as Node.js application
1. Install Node.js 16+ if not already installed
2. Run `npm install` to install dependencies
3. Run `npm start` to start the server
4. Access the website at http://localhost:3000 (or the PORT specified in .env)

### Option 2: Deploy as static site
1. Copy all files from the `public` folder to your web server's root directory
2. Configure your web server to handle SPA routing (redirect all requests to index.html)

### Option 3: Deploy to a cloud provider

#### Heroku
```
heroku create
git init
git add .
git commit -m "Initial commit"
heroku git:remote -a your-heroku-app-name
git push heroku main
```

#### Vercel or Netlify
Simply drag and drop the `public` folder to the Vercel or Netlify dashboard.

## Structure
- `public/` - Contains all static assets for the website
- `server.js` - Simple Express server for hosting the website
- `package.json` - Node.js package configuration

## Contact
For any questions regarding this website deployment, please contact:
info@nexsbiomedica.com
