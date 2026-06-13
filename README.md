# 🚀 HTML Tester Pro

A professional, browser-based playground for testing complex HTML, CSS, and JavaScript projects with multi-file support.

## 🌟 Features

- **Multi-File Virtual System (VFS)**: Manage a full project structure with multiple files. No need for a backend or server.
- **Integrated File Explorer**: 
  - Create new files (`.html`, `.css`, `.js`) on the fly.
  - Quick-switch between files with a single click.
  - Easily delete unused files from your project.
- **Smart Bundling Engine**: 
  - Automatically gathers all `.css` files and injects them as `<style>` blocks.
  - Automatically gathers all `.js` files and injects them as `<script>` blocks.
  - All files are bundled into the `index.html` entry point for instant rendering.
- **Pro Split-Screen Interface**: Three-pane layout featuring a File Explorer, a Code Editor, and a Live Preview window.
- **Power User Workflow**: Support for `Ctrl + Enter` to quickly execute and render your project.
- **Zero Installation**: Runs entirely in your browser—no dependencies, no build steps, no setup.

## 🛠️ How It Works

The app simulates a real development environment using a **Virtual File System (VFS)**. 

1. **State Management**: All files and their contents are stored in a JavaScript object.
2. **The Build Process**: When you click **Run**, the app performs a "build" step:
   - It starts with the content of `index.html`.
   - It scans the VFS for any files ending in `.css` and appends their content to a generated `<style>` tag in the `<head>`.
   - It scans for any files ending in `.js` and appends their content to a generated `<script>` tag at the end of the `<body>`.
3. **Isolated Rendering**: The final bundled HTML is injected into an `<iframe>` using the `srcdoc` attribute, ensuring a clean and isolated preview.

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari).

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/adhithyan-pradeep/HTML-tester.git
   ```
2. Navigate to the project folder:
   ```bash
   cd HTML-tester
   ```
3. Open `index.html` in your preferred browser.
4. Create your files in the explorer, write your code, and click **Run**!

## 🎨 Interface Design
- **Sidebar**: A dark-themed explorer for managing your project files.
- **Editor**: A focused, dark-mode environment for writing clean code.
- **Preview**: A high-contrast white-background window to see your work exactly as it would appear on a live website.

## 📜 License
This project is open-source and available under the MIT License.
