# Keeper

A simple and elegant note-taking application built with React and Vite.

## Description

Keeper is a lightweight note-taking app that allows users to view and manage notes with a clean, intuitive interface. Each note displays a title and content, making it easy to organize and access your thoughts and ideas.

## Features

- 📝 Display multiple notes with titles and content
- 🎨 Clean and modern UI with custom styling
- ⚡ Fast performance powered by Vite
- 📱 Responsive design
- 🔤 Custom fonts (McLaren, Montserrat)

## Tech Stack

- **Frontend Framework**: React 17
- **Build Tool**: Vite 5
- **Styling**: CSS
- **Language**: JavaScript (JSX)

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn

## Installation

1. **Clone the repository** (if applicable)
   ```bash
   git clone <repository-url>
   cd Keeper
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

## Getting Started

### Development Server

Start the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or the port Vite assigns).

### Build for Production

Build the application:
```bash
npm run build
```

The optimized build will be generated in the `dist/` directory.

### Preview Production Build

Preview the production build locally:
```bash
npm run preview
```

### Linting

Check for code quality issues:
```bash
npm run lint
```

## Project Structure

```
Keeper/
├── index.html              # Main HTML file
├── package.json            # Project dependencies and scripts
├── vite.config.js          # Vite configuration
├── public/
│   └── styles.css          # Global styles
├── src/
│   ├── index.jsx           # React entry point
│   ├── notes.js            # Sample notes data
│   └── components/
│       ├── App.jsx         # Main App component
│       ├── Header.jsx      # Header component
│       ├── Footer.jsx      # Footer component
│       └── Note.jsx        # Individual note component
```

## How to Add Notes

Notes are stored in [`src/notes.js`](src/notes.js). To add a new note, add an object to the `notes` array:

```javascript
{
  key: 6,
  title: "Your Title",
  content: "Your note content here"
}
```

Each note object requires:
- **key**: Unique identifier (number)
- **title**: Note title (string)
- **content**: Note content (string)

## Components

### App.jsx
Main component that renders the header, notes, and footer.

### Header.jsx
Displays the app title "Keeper" at the top of the page.

### Note.jsx
Renders individual note cards with title and content.

### Footer.jsx
Displays copyright information with the current year.

## Styling

Global styles are defined in [`public/styles.css`](public/styles.css). Key styling features:
- Yellow header with shadow
- White note cards with shadow
- Responsive layout
- Custom fonts from Google Fonts

## Contributing

1. Create a feature branch (`git checkout -b feature/AmazingFeature`)
2. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
3. Push to the branch (`git push origin feature/AmazingFeature`)
4. Open a Pull Request

## License

This project is open source and available under the MIT License.

## Support

For issues or questions, please open an issue in the repository.

---

**Happy Note-Taking! 📝**
