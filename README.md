# My Electron App v2.0

[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/sandunMadhushan)

Welcome to **My Electron App**! 🚀 This project is an Electron-based desktop application designed to showcase how web technologies (HTML, CSS, and JavaScript) can be used to build cross-platform desktop apps. Whether you're new to Electron or a seasoned developer, this app provides a great starting point to explore and learn.

---

## Features

- **Cross-Platform**: Runs on Windows, macOS, and Linux.
- **Web Technologies**: Built using HTML, CSS, and JavaScript.
- **Interactive UI**: Includes buttons, alerts, and basic interactivity.
- **Electron Integration**: Demonstrates how to manage windows and app lifecycle with Electron.

---

## Getting Started

Follow the steps below to clone, install, and run this project on your system:

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/sandunMadhushan/my-electron-app.git
```

Navigate to the project directory:

```bash
cd my-electron-app
```

### 2. Install Dependencies

Before running the app, install the necessary dependencies using `npm`:

```bash
npm install
```

### 3. Run the Application

Start the Electron application with:

```bash
npm start
```

This will launch the app in a new desktop window.

---

## Folder Structure

Here's a quick overview of the project structure:

```
my-electron-app/
├── .gitignore            # Files and folders to ignore in Git
├── .gitattributes        # Git LFS tracking information
├── index.html            # Main HTML file for the app
├── main.js               # Electron main process code
├── package.json          # Project metadata and scripts
├── package-lock.json     # Dependency tree
├── script.js             # App functionality (JavaScript)
├── style.css             # Styling for the app
└── node_modules/         # Installed dependencies (ignored in Git)
```

---

## How to Package the App

If you'd like to distribute this app to others, you can package it:

1. Install `electron-packager`:

   ```bash
   npm install -g electron-packager
   ```

2. Package the app:
   ```bash
   electron-packager . MyElectronApp
   ```

This creates a distributable version of the app in a folder named `MyElectronApp`.

---

## Contributing

Feel free to contribute! Open issues, suggest features, or submit pull requests. Let’s make this project even better together.

---

## Support

If you encounter any issues, please feel free to open an issue on [GitHub](https://github.com/sandunMadhushan/my-electron-app/issues).

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/sandunMadhushan/my-electron-app/blob/main/LICENSE) file for details.

---

Enjoy building with Electron! 💻
