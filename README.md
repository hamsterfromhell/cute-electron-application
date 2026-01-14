

```
electron-app-template
├── node_modules
├── main.js
├──index.html
├── styles.css
├── script.js
├── package.json
└── package-lock.json
```

### Core Files

- **`main.js`**
    
    Electron’s main process. Creates the app window and loads the HTML file.
    
- **`index.html`**
    
    The main UI layout of  desktop app.
    
- **`styles.css`**
    
    Styles for your app UI, including draggable window behavior.
    
- **`script.js`**
    
    Frontend JavaScript logic for interactivity.
    
- **`package.json`**
    
    App configuration, dependencies, and run scripts.


---

## Prerequisites

Before using this template, make sure you have:

- **Node.js**
- **Homebrew** (macOS)
- A code editor (VS Code recommended)

---

## Step by step set up

### 1. Install Package Managers (if you don’t have one on your computer)

MacOS: Homebrew ([https://brew.sh](https://brew.sh/))

Window: Chocolatey (https://chocolatey.org/install)

### 2. Install Node.js

You can install Node.js in two ways:

### Option A: Use a package manager (mine is Homebrew which I used in the tutorial)

```bash
brew install node
```

Verify installation:

```bash
node -v
npm -v
```

If both commands return version numbers, you’re good to go 

### Option B: Download Installer

Download Node.js directly from: https://nodejs.org

and follow their installation instructions.


### 3. Clone This Repo

```bash
gitclone https://github.com/nasha-wanich/electron-app-template.git
cd electron-app-template
```

### 4. Install Dependencies

```bash
npm install
```

### 5. Run the App

```bash
npm run start
```

This will launch a simple Electron desktop window.

---

## Next Steps

- Modify `index.html` to build your app layout
- Style your app UI in `styles.css`
- Add your app logic in `script.js`
- Adjust window behavior in `main.js`  (ex. size, transparency etc.)


