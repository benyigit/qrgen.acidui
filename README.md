# SYS.QR_GEN

SYS.QR_GEN is a modern QR code generator built on the **Acid UI** philosophy, featuring industrial aesthetics and a retro-futuristic design. 

This project offers users a unique visual experience with its terminal-like interface, monospace typography, and Acid Green accents, while instantly converting your links and text payloads into high-resolution QR codes.

## 🧪 What is Acid UI?
**Acid UI** is an experimental design system that blends brutalist and technical UI elements, drawing inspiration from futuristic terminal interfaces. By using sharp edges, dark backgrounds, thin neon grids, and monospaced fonts, it creates a direct, unembellished, "hacked" or "raw" feeling between the system and the user.

In this project, the following components and design rules provided by Acid UI are used:
- **Acid/Neon Color Palette:** `#ccff00` (Acid Green) and dark terminal backgrounds.
- **Technical Surfaces:** Framed panels, angular input fields.
- **Interactive Feedback:** Blinking cursors and glowing buttons that reinforce the terminal illusion.
- **Components:** Customized button, card, and input architectures using the `acidui-core` dependency.

## 🚀 Features
- **Instant QR Generation:** Generates a QR code dynamically the moment you type your payload.
- **Customization:** Customize the **Foreground** (FG_HEX) and **Background** (BG_HEX) colors of your QR code.
- **Cache History:** Utilizes local storage to save your recently generated QR codes under the "CACHE_DATA" panel, allowing you to restore them with a single click.
- **Quick Extraction:** Export your generated QR codes in high quality to your system using the `EXTRACT_PNG` button.

## 🛠 Setup and Launch

Follow these steps to run the project on your local machine.

### 1. Install Dependencies
To install the project dependencies, run the following command in your terminal at the root directory of the project:
```bash
npm install
```

*(If you receive a missing module warning regarding the `acidui-core` package, you can reinstall it using the command `npm i acidui-core`.)*

### 2. Start the Development Server
Once dependencies are installed, you can start the application in your local environment:
```bash
npm run dev
```

### 3. Open in Browser
Depending on the output in the terminal (usually `http://localhost:5173/`), you can paste this address into your browser to start using SYS.QR_GEN right away. When you make changes to the code (for example, modifying colors to suit your Acid theme preference), the page will update automatically.

## ⚙️ Stack & Architecture
- **React.js / Vite:** Fast development environment.
- **Framer Motion:** For smooth animation transitions and micro-interactions in UI components.
- **Lucide React:** Minimalist and technical system icons.
- **QR Code SVG:** Customized and vector-based QR rendering system.
- **AcidUI Core:** Interface design skeleton and industrial brutalist styles.

---
*Terminal Closed. // STATUS: SYSTEM RUNNING*
