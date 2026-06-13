# 🚀 HTML Tester

A lightweight, browser-based playground for testing HTML, CSS, and JavaScript snippets in real-time.

## 🌟 Features

- **Split-Screen Interface**: Efficiently code on the left and see your results on the right.
- **Manual Execution**: A dedicated **Run** button at the top center ensures you control exactly when the code updates.
- **Keyboard Shortcuts**: Support for `Ctrl + Enter` to quickly execute code without leaving the keyboard.
- **Full Web Support**: Write complete HTML documents including `<style>` and `<script>` tags.
- **Zero Installation**: No dependencies or build steps required—runs directly in any modern web browser.

## 🛠️ How It Works

The app uses a `textarea` as the code editor and an `<iframe>` for the preview window. When the **Run** button is clicked, the content of the editor is injected into the iframe using the `srcdoc` attribute, providing a clean and isolated environment for rendering the HTML.

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
4. Start coding in the left pane and click **Run**!

## 🎨 Interface Design
- **Header**: Fixed top bar containing the primary action button.
- **Left Pane**: Dark-themed code editor for better focus and reduced eye strain.
- **Right Pane**: White-background preview window simulating a real browser page.

## 📜 License
This project is open-source and available under the MIT License.
