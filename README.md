<div align="center">
  <h1>✨ dotG's Custom VSCode Setup ✨</h1>
  <p>
    <strong>Transform your coding experience with hand-crafted Visual Studio Code customizations</strong>

<https://github.com/user-attachments/assets/d2280779-46b2-40d2-acc3-82f9841822d7>

  </p>
</div>

## 🌟 Introduction

Welcome to my curated repository of Visual Studio Code configurations and customizations. Inside, you'll find a comprehensive guide to setting up your Visual Studio Code for customization, along with recommended extensions, tailored settings, and custom CSS/JS modifications that will transform your coding environment. 😎

## What's Inside 🔍

<details open>
<summary><strong>Repository Contents</strong></summary>

- **🧩 Extensions:** All Extension are backed inside the my VSCode Profile.
- **⚙️ Settings & Configurations:** Detailed instructions for replicating my Visual Studio Code setup including custom tweaks
- **🎨 Custom Theming:** CSS and JS files for a personalized coding experience

</details>

## Getting Started 🚦

<details open>
<summary><strong>Step-by-step Installation Guide</strong></summary>

### Prerequisites

- Windows operating system
- Visual Studio Code installed (or planning to install)

### Installation Steps

1. **Download My Font:**
   - Install the **dotG Mono** font from: [github.com/SharifdotG/dotG-Mono](https://github.com/SharifdotG/dotG-Mono)

2. **Install VSCode (If needed):**
   - Download and install from [code.visualstudio.com](https://code.visualstudio.com/)

3. **Import My VSCode Profile:**
   - Copy my Profile Template URL:

     ```
     https://insiders.vscode.dev/profile/github/927f6b4d7474ff1a6103255761543259
     ```

   - Follow the import instructions at [code.visualstudio.com/docs/editor/profiles](https://code.visualstudio.com/docs/editor/profiles)

4. **Download Custom Files:**
   - Get [custom-vscode.css](/custom-vscode.css) and [vscode-script.js](/vscode-script.js)
   - Place them in a folder named `VSCode_Custom` in your Documents folder

5. **Update Settings:**
   - Press `Ctrl + Shift + P` and type `Preferences: Open User Settings (JSON)`
   - Add the following to your `settings.json`:

     ```json
     "vscode_custom_css.imports": [
       "file:///C:/Users/<user_name>/Documents/VSCode_Custom/custom-vscode.css",
       "file:///C:/Users/<user_name>/Documents/VSCode_Custom/vscode-script.js",
       "file:///c:/Users/<user_name>/.vscode-insiders/extensions/brandonkirbyson.vscode-animations-2.0.7/dist/updateHandler.js"
     ],
     ```

6. **Replace Path:**
   - Change `<user_name>` to your Windows username or correct path

7. **Enable Custom CSS and JS:**
   - Press `Ctrl + Shift + P`
   - Type `Enable Custom CSS and JS` and select it
   - Restart VSCode when prompted

8. **Troubleshooting:**
   - If you see errors, verify the paths in `settings.json`
   - When successful, you'll have custom CSS and JS installed! 🎉

9. **Customize:**
   - Modify `custom-vscode.css` and `vscode-script.js` to your preference 🎨

10. **Enjoy:**
    - You're all set with your new and improved Visual Studio Code setup! 🚀

</details>

## Screenshots 📷

<div align="center">

### VSCode Interface 🖥️

<img src="/Placeholder/Example.png" alt="VSCode Screenshot" width="800"/>

### Configuration Details 🧰

<img src="/Placeholder/Configuration.png" alt="Configurations Screenshot" width="800"/>

</div>

## 🌐 Connect & Contribute

Feel free to fork this repository, submit PRs, or suggest improvements!

---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/SharifdotG">SharifdotG</a></p>
  <p>Happy coding! 🎉</p>
</div>
