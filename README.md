# Chatbot Client

Independent HTML/CSS/JavaScript frontend for the chatbot application.

## Setup

1. Open `index.html` in your web browser, or
2. Serve using a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

Then open `http://localhost:8000` (or `http://localhost:8080` for http-server)

## Configuration

Update the `API_BASE_URL` in `client.js` to point to your server:

```javascript
const API_BASE_URL = 'http://your-server-url:3000';
```

## Features

- Clean, modern UI with gradient design
- Real-time chat messaging
- Auto-scrolling message container
- Responsive design for mobile and desktop
- Error handling with user-friendly messages

## Deployment

Deploy these files to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Firebase Hosting
- Any web server (Apache, Nginx, etc.)

Just make sure to update `API_BASE_URL` in `client.js` to point to your deployed server.
