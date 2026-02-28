# 🎬 Moviedux

**Live Demo:** [https://GhantaParamita.github.io/Moviedux](https://GhantaParamita.github.io/Moviedux)

Find your next favorite movie! Moviedux is a React-powered movie discovery and watchlist application that helps you explore movies, check ratings, and keep track of films you want to watch.

## ✨ Features

- 🎥 Browse a curated collection of movies
- ⭐ View movie ratings and genre information
- 📋 Add/remove movies from your personal watchlist
- 🎹 Responsive and intuitive UI
- 📱 Works seamlessly on desktop and mobile devices
- 🚀 Deployed on GitHub Pages for instant access

## 🛠️ Technologies & Tools

- **Framework:** React 18.2.0
- **Routing:** React Router DOM 6.22.3
- **Build Tool:** Create React App (react-scripts 5.0.1)
- **Deployment:** GitHub Pages (gh-pages 6.3.0)
- **Testing:** Jest & React Testing Library
- **Performance:** Web Vitals

## 📁 Project Structure

```
src/
├── components/
│   ├── Header.js          # App header with logo
│   ├── Footer.js          # App footer
│   ├── MovieCard.js       # Individual movie card
│   ├── MoviesGrid.js      # Grid of movies
│   └── Watchlist.js       # Watchlist page
├── App.js                 # Main app component
├── App.css                # App styles
├── styles.css             # Global styles
└── index.js               # Entry point

public/
├── images/                # Movie poster images
├── movies.json            # Movie data
└── index.html             # HTML template
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm

### Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/GhantaParamita/Moviedux.git
   cd Moviedux
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

## 📝 Available Scripts

### `npm start`

Runs the app in development mode. The page reloads when you make changes.

### `npm test`

Launches the test runner in interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder with optimizations.

### `npm run deploy`

Deploys the app to GitHub Pages. Run this to update the live site.

### `npm run eject`

**Note:** This is a one-way operation. Use only if you need full control over configuration.

## 🌐 Deployment

This project is deployed on GitHub Pages. To deploy your own version:

1. Update the `homepage` URL in `package.json` to your GitHub Pages URL
2. Run:
   ```bash
   npm run build
   npm run deploy
   ```

## 📊 Data Source

Movie data is stored in `public/movies.json` and includes:

- Movie ID, title, genre, release year
- Movie poster images
- Rating information

## 🎨 Customization

- Edit movie data in `public/movies.json`
- Add/update movie images in `public/images/`
- Modify styles in `src/App.css` and `src/styles.css`
- Add new components in `src/components/`

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Paramita Ghanta**

- GitHub: [GhantaParamita](https://github.com/GhantaParamita)

---

Enjoy discovering your next favorite movie! 🍿🎬

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
