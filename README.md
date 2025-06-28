# Eat-n-Split

Eat-n-Split is a React-based web application designed to help users easily split bills and manage shared expenses among friends or groups. The app provides a simple and intuitive interface for adding expenses, tracking who owes what, and ensuring everyone pays their fair share.

## Features

- Add and manage friends or group members.
- Record expenses and assign them to specific people.
- Automatically calculate how much each person owes or is owed.
- Simple, clean, and responsive user interface.
- Built with React for fast and interactive user experience.

## Project Structure

```
Eat-n-Split/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.js
│   ├── index.css
│   └── index.js
├── .gitignore
├── package.json
└── README.md
```

- **public/**: Contains static assets and the main HTML file.
- **src/**: Contains the React source code.
  - `App.js`: Main React component where the app logic resides.
  - `index.js`: Entry point for the React app.
  - `index.css`: Global styles for the app.
- **package.json**: Project metadata and dependencies.
- **.gitignore**: Specifies files and directories to be ignored by Git.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. **Clone the repository:**

   ```powershell
   git clone <your-repo-url>
   cd Eat-n-Split
   ```

2. **Install dependencies:**

   ```powershell
   npm install
   ```

3. **Start the development server:**
   ```powershell
   npm start
   ```
   This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Building for Production

To build the app for production, run:

```powershell
npm run build
```

This will create an optimized build in the `build/` directory.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
