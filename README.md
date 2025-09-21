# Nithish-Impactfolio
My Portfolio Resume Website

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nithishnagaraj/Nithish-Impactfolio.git
   cd Nithish-Impactfolio
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Build for Production
```bash
npm run build
```

## Deployment to GitHub Pages

This project is configured for deployment to GitHub Pages.

### Automatic Deployment
1. Ensure you have the correct repository URL in `package.json` homepage field.
2. Run the deploy command:
   ```bash
   npm run deploy
   ```

This will build the project and deploy it to GitHub Pages.

### Manual Deployment
1. Build the project:
   ```bash
   npm run build
   ```
2. Install gh-pages if not already installed:
   ```bash
   npm install -g gh-pages
   ```
3. Deploy:
   ```bash
   gh-pages -d build
   ```

The site will be available at: https://nithishnagaraj.github.io/Nithish-Impactfolio/

## Customization

Edit the content in `src/content_option.js` to personalize:
- Personal information
- Skills
- Portfolio items
- Contact details
- Social media links

## Technologies Used
- React
- React Router
- Bootstrap
- EmailJS
- Typewriter Effect
