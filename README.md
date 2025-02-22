VS Code Customization Settings
#Demo Photo:
![Screenshot 2025-02-23 044517](https://github.com/user-attachments/assets/d48619d7-92fb-4574-842f-ce6a4363c399)


This repository contains my personalized VS Code settings designed to create a streamlined and efficient development environment. The configuration includes an Andromeda theme, essential extensions, and enhanced productivity settings for a variety of languages.

## 🌟 Features

- **Visual Theme**: Andromeda color theme with custom UI modifications for better aesthetics and focus.
- **Productivity Boost**:
  - Auto-formatting with Prettier for consistent code style.
  - Smart code completion for faster development.
  - Integrated terminal setup for seamless workflow.
- **Language Support**:
  - JavaScript/TypeScript
  - Python/C/C++
  - Web (HTML/CSS/SCSS)
  - Markdown/YAML/GraphQL
- **Workflow Enhancements**:
  - Live Server integration for instant previews.
  - Code Runner configuration for running code snippets in various languages.
  - Advanced Emmet support for faster HTML/CSS development.

## 🛠️ Installation

To set up the environment on your machine, follow these steps:

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/andromeda-dev-environment.git
```

### 2. Copy Settings to Your Project Directory

After cloning, copy the `.vscode` folder into your desired project directory:

```bash
cp -r andromeda-dev-environment/.vscode ~/your-project-directory/
```

### 3. Install Required Extensions

Based on your settings.json code, here are the extensions you'll need:

1. Andromeda Theme
2. Material Icon Theme
3. Prettier
4. Live Server
5. Code Runner
   Here is a list of recommended extensions for this setup. You can install them manually or use the following `extensions.json` configuration:
   extensions.json File:

```json
{
  "recommendations": [
    "esbenp.prettier-vscode",
    "ms-vscode.cpptools",
    "ms-python.python",
    "ritwickdey.liveserver",
    "formulahendry.code-runner"
  ]
}
```

## 🎨 Customization Guide

### Font Installation

1. Download [JetBrains Mono](https://www.jetbrains.com/lp/mono/).
2. Install it system-wide.
3. Update VS Code settings to use JetBrains Mono:

```json
"editor.fontFamily": "JetBrains Mono"
```

### Theme Configuration

To further customize your theme settings, add this to your `settings.json`:

```json
"workbench.colorCustomizations": {
  "tab.activeBackground": "#706fd3",
  "statusBar.background": "#474787"
}
```

## ⚙️ Key Configuration Highlights

| Category        | Setting          | Value            |
| --------------- | ---------------- | ---------------- |
| **Editor**      | Font Size        | 16px             |
| **Formatting**  | Auto-save Delay  | 800ms            |
| **Terminal**    | Font Family      | Cascadia Code PL |
| **UI**          | Sidebar Location | Right            |
| **Performance** | Minimap          | Disabled         |

## 🔌 Required Extensions

Make sure to install these essential extensions for the best experience:

1. [Andromeda Theme](https://marketplace.visualstudio.com/items?itemName=EliverLara.andromeda)
2. [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
3. [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
4. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## 🤝 Contributing

If you’d like to contribute to this repository, follow these steps:

1. Fork the repository.
2. Create a feature branch:  
   `git checkout -b feature/improvement`
3. Commit your changes:  
   `git commit -m 'Add some feature'`
4. Push to your branch:  
   `git push origin feature/improvement`
5. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- **Andromeda Theme** by Oliver Lara
- **JetBrains Mono** typeface for improved readability.
- **Microsoft VS Code** team for building such a great IDE.

---

## Additional Recommendations

### 1. **Include Screenshots**:

Showcase how your setup looks by adding screenshots:

- Editor layout and color theme.
- Integrated terminal configuration.
- Code in different languages with the theme applied.

### 2. **Extension Management**:

If you want to track your installed extensions, run the following command to generate a list:

```bash
# Generate extension list
code --list-extensions > extensions.txt
```

### 3. **Version Compatibility**:

You can create a `vscode-compatibility.md` file with:

- Minimum required VS Code version.
- Operating system requirements.
- Extension version recommendations.

### 4. **Setup Script (Optional)**:

For automatic setup, consider adding a setup script like:

```bash
#!/bin/bash
cp .vscode/settings.json ~/.config/Code/User/
```

## Author

Nazrul Islam
mhdnazrul511@gmail.com

#Demo Photo:
![Screenshot 2025-02-23 044557](https://github.com/user-attachments/assets/62725b82-4bbd-425a-9751-7a090a0023f1)
![Screenshot 2025-02-23 044546](https://github.com/user-attachments/assets/68177cce-1c3f-4589-8edf-d6321c37e35d)
![Screenshot 2025-02-23 044535](https://github.com/user-attachments/assets/0460e8a2-2549-4fea-bced-b06e52d47baf)
![Screenshot 2025-02-23 044526](https://github.com/user-attachments/assets/0434d476-5a26-457f-a6d7-a4c9cbea6733)
![Screenshot 2025-02-23 044517](https://github.com/user-attachments/assets/811677fd-787e-4aa4-9015-6bcd4135d16c)

