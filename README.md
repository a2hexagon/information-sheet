# Information Sheet - PWA

A Progressive Web App for client onboarding in the Digital Presence portal.

## Features

- Multi-step form for client information collection
- PDF receipt generation
- Netlify Forms integration for form submissions
- Offline functionality with fallback PDF generation
- Installable as a mobile app
- Responsive design

## Form Submission

The app uses Netlify Forms for handling form submissions when online. When offline, it generates a PDF receipt locally. The form includes:

- Spam protection via honeypot field
- Automatic PDF generation on submission
- Offline fallback functionalitymobile app
- Responsive design

## Form Submission

The app uses Netlify Forms for handling form submissions when online. When offline, it generates a PDF receipt locally. The form includes:

- Spam protection via honeypot field
- Automatic PDF generation on submission
- Offline fallback functionality

## Installation

1. Clone the repository
2. Serve the files using a local server (HTTPS required for full PWA features)
3. Access the app in a modern browser

## PWA Features

- **Manifest**: Defines app metadata and icons
- **Service Worker**: Enables offline caching and background sync
- **Installable**: Can be installed on mobile devices and desktops
- **Responsive**: Works on all screen sizes

## Setup Notes

- Replace the placeholder icon files in `/icons/` with actual PNG images (192x192 and 512x512)
- For production, serve over HTTPS to enable all PWA features

## Development

To run locally:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Browser Support

Works in all modern browsers that support Service Workers and Web App Manifests.
