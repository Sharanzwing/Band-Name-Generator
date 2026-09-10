# 🎸 Band Name Generator

> A modern, sleek web application that dynamically generates catchy, stage-ready band names with an electric rock-and-roll vibe.

![Node.js](https://img.shields.io/badge/Node.js-v18+-68a063?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-v4.18-000000?style=for-the-badge&logo=express&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-v3.1-b4ca65?style=for-the-badge&logo=ejs&logoColor=white)
![License](https://img.shields.io/badge/License-ISC-blue?style=for-the-badge)

---

## ✨ Features

- ⚡ **Instant Band Name Creation**: Randomly pairs punchy adjectives with powerful nouns for unique monikers.
- 🎨 **Electric Stage Aesthetic**: Ambient stage lighting, glassmorphism cards, vibrant neon gradients, and bold typography powered by Google Fonts (*Syne* & *Outfit*).
- 📱 **Fully Responsive**: Seamlessly scales across phones, tablets, and desktop displays.
- 🚀 **Server-Side Rendered**: Lightweight and fast templating using Express and EJS partials.

---

## 🚀 Quick Start

### 1. Prerequisites
Make sure you have [Node.js](https://nodejs.org/) (v16 or newer) installed.

### 2. Installation
Clone this repository or open the project folder in **GitHub Desktop**:

```bash
git clone https://github.com/your-username/band-name-generator.git
cd band-name-generator
```

Install dependencies:
```bash
npm install
```

### 3. Running the Application
Start the server:
```bash
npm start
```

Open your browser and navigate to:
```
http://localhost:5000
```

---

## 📁 Project Structure

```
├── index.js             # Express application and name generation logic
├── package.json         # Project metadata and dependencies
├── .gitignore           # Git ignore configuration
├── public/
│   └── styles/
│       └── main.css     # Design system, glassmorphism, animations & responsiveness
└── views/
    ├── index.ejs        # Main generator view
    └── partials/
        ├── header.ejs   # HTML head, Google Fonts, and ambient stage glow
        └── footer.ejs   # Dynamic copyright and footer branding
```

---

## 🛠️ Built With

- **[Node.js](https://nodejs.org/)** - JavaScript runtime environment
- **[Express](https://expressjs.com/)** - Fast, unopinionated web framework for Node.js
- **[EJS](https://ejs.co/)** - Embedded JavaScript templating engine
- **CSS3** - Glassmorphism, animations, CSS custom properties, and responsive flexbox

---

## 📄 License

This project is licensed under the ISC License.
