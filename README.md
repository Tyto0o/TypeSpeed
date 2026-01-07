# TypeSpeed ⌨️

A modern, interactive typing speed test application that helps you measure and improve your typing skills. Test your words per minute (WPM), accuracy, and challenge yourself with different game modes! 

![JavaScript](https://img.shields.io/badge/JavaScript-54.9%25-yellow)
![HTML](https://img.shields.io/badge/HTML-24.0%25-orange)
![SCSS](https://img.shields.io/badge/SCSS-21.1%25-pink)

## ✨ Features

- **Two Game Modes**
  - **Minute Test**: Race against the clock!  Type as much as you can in 60 seconds
  - **Full Text Mode**: Complete the entire text at your own pace
  
- **Real-time Statistics**
  - Words Per Minute (WPM)
  - Characters Per Minute (CPM)
  - Accuracy percentage
  - Remaining time tracker

- **Instant Feedback**
  - Visual indicators for correct and incorrect characters
  - Live accuracy tracking as you type
  - Comprehensive results summary after completion

- **Beautiful UI**
  - Clean, modern design with smooth animations
  - Custom color scheme with pink and purple accents

## 🚀 Live Demo

Experience TypeSpeed in action:  [Live Demo](https://tyto0o.github.io/TypeSpeed/)

## 🛠️ Built With

- **HTML5** - Semantic markup structure
- **SCSS** - Advanced styling with Sass preprocessing
- **JavaScript** - Dynamic game logic and real-time calculations
- **Gulp** - Task automation and build process
- **Babel** - JavaScript transpilation for browser compatibility

## 📦 Installation

1. Clone the repository: 
```bash
git clone https://github.com/Tyto0o/TypeSpeed.git
cd TypeSpeed
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
gulp
```

4. Open your browser and navigate to the local development server (typically `localhost:3000`)

## 🎮 How to Use

1. **Choose Your Mode**:  Select either "Minute test" or "Finish text" from the start screen
2. **Start Typing**: Click on the text area and begin typing the displayed text
3. **Track Progress**: Watch your WPM, CPM, and accuracy update in real-time
4. **View Results**: After completing the test, see your final statistics
5. **Try Again**: Use the buttons to retry or return to the home screen

## 📊 Statistics Explained

- **WPM (Words Per Minute)**: The standard measure of typing speed.  Calculated as (correct characters / 5) / minutes
- **CPM (Characters Per Minute)**: Total number of characters typed per minute
- **Accuracy**:  Percentage of correctly typed characters

## 🏗️ Project Structure

```
TypeSpeed/
├── dist/              # Compiled production files
│   ├── css/           # Minified CSS
│   └── js/            # Minified JavaScript
├── src/               # Source files
│   ├── js/            # JavaScript modules
│   │   ├── gameLogic.js
│   │   └── randomSentences.js
│   └── scss/          # SCSS stylesheets
├── index.html         # Main HTML file
├── gulpfile.js        # Gulp configuration
└── package.json       # Project dependencies
```

## 🔧 Development

The project uses Gulp for build automation.  Available tasks include: 

- SCSS compilation and minification
- JavaScript transpilation with Babel
- Autoprefixer for CSS compatibility
- Live browser reload with BrowserSync
- Source maps generation

## 📝 License

This project is licensed under the ISC License. 
