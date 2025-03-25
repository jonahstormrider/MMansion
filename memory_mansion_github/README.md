# Memory Mansion - GitHub Pages Deployment

This repository contains the Memory Mansion 3D application, an interactive memory palace for learning about investment vehicles with an Assassin's Creed aesthetic.

## About Memory Mansion

Memory Mansion is an interactive 3D environment that helps you learn and remember investment vehicles through spatial memory techniques. The application features:

- First-person navigation through a detailed mansion
- Interactive objects that provide information about investment vehicles
- Assassin's Creed-inspired features like Eagle Vision and Synchronization Points
- Dialogue system for displaying investment information

## Local Development

To run this project locally:

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm start
   ```
4. Open your browser and navigate to `http://localhost:3000`

## Deployment

This repository is configured for easy deployment to GitHub Pages or Vercel.

### GitHub Pages Deployment

1. Go to the repository Settings
2. Navigate to the "Pages" section
3. Select the main branch as the source
4. Click Save

Your site will be published at `https://[your-username].github.io/[repository-name]/`

### Vercel Deployment

1. Import this repository to Vercel
2. Vercel will automatically detect the configuration
3. Deploy with default settings

## Project Structure

- `/assets` - Contains all textures, sounds, and the main JavaScript bundle
- `/api` - Contains the server code for local development and Vercel deployment
- `index.html` - Main entry point for the application
- `vercel.json` - Configuration for Vercel deployment

## License

MIT
