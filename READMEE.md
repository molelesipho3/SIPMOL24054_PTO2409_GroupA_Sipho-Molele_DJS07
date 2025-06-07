# Meme Generator

A simple React application that allows you to create memes by adding custom text to random meme images.

## Quick start:

```
$ npm install
$ npm run build
```

## Development

Run Webpack in watch-mode to continually compile the JavaScript as you work:

```
$ npm run watch
```

## Features

- Fetches popular meme images from the imgflip API
- Allows adding custom top and bottom text to memes
- Responsive design that works on all devices

## Project Structure

```
meme-generator/
├── components/       # React components
│   ├── Header.js     # Header component with logo
│   └── Meme.js       # Main meme generator component
├── images/           # Static images
│   └── troll-face.png # Logo image
├── App.js            # Main App component
├── index.js          # Entry point
├── index.html        # HTML template
├── style.css         # Styles
└── webpack.config.js # Webpack configuration
```

## How to Use

1. Run the application using the instructions above
2. Enter text in the "Top text" and "Bottom text" fields
3. Click "Get a new meme image" to change the meme template
4. Your meme will be displayed with your custom text

Enjoy creating memes!

