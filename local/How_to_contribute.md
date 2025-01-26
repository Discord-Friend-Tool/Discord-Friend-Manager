# Contributing to Discord Friend Manager Translations 🌍

Thank you for your interest in contributing to **Discord Friend Manager**! 🎉 We’re thrilled to have you join our mission to make the application accessible in more languages.

## Table of Contents 📚

- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
  - [1. Fork and Clone the Repository](#1-fork-and-clone-the-repository)
  - [2. Navigate to the Local Folder](#2-navigate-to-the-local-folder)
  - [3. Copy the Template File](#3-copy-the-template-file)
  - [4. Translate the Content](#4-translate-the-content)
  - [5. Test Your Translation (Optional)](#5-test-your-translation-optional)
  - [6. Submit a Pull Request](#6-submit-a-pull-request)
- [Guidelines 📋](#guidelines-)
- [Get Recognized! 🏅](#get-recognized-)
- [Need Help?](#need-help)

## Getting Started 🚀

Before you begin, ensure you have [Git](https://git-scm.com/) installed on your machine.

## How to Contribute

Follow these simple steps to contribute to the translations:

### 1. Fork and Clone the Repository

Fork the repository on GitHub and clone it to your local machine:

```bash
git clone https://github.com/YourUsername/Discord-Friend-Manager.git
cd Discord-Friend-Manager/local
```

### 2. Navigate to the Local Folder

Inside the cloned repository, go to the `local` folder where all translation files are stored.

### 3. Copy the Template File

Use the provided `lang-LANG.json` file as a base. Copy and rename the file to match the language you want to translate.

Replace `LANG` with the appropriate [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) language code. For example:

- **German**: `lang-DE.json`
- **Spanish**: `lang-ES.json`

**Example:**

```bash
cp lang-LANG.json lang-DE.json
```

### 4. Translate the Content

Open the copied file in your favorite text editor and replace the English text with the corresponding translations. **Ensure you maintain the JSON structure.**

**Example:**

```json
{
  "LanguageName": "Deutsch",
  "ButtonShow": "Anzeigen",
  "ButtonHide": "Ausblenden",
  "ButtonLogin": "Anmelden"
}
```

### 5. Test Your Translation (Optional)

To ensure your JSON file is valid, use an online JSON validator like [JSONLint](https://jsonlint.com/).

### 6. Submit a Pull Request

Once you have finished translating:

1. **Commit Your Changes:**

    ```bash
    git add lang-DE.json
    git commit -m "Add German translation"
    git push origin main
    ```

2. **Create a Pull Request:**

    - Go to your forked repository on GitHub.
    - Click on the **Compare & pull request** button.
    - Provide a clear description of your changes.
    - Submit the pull request.

## Guidelines 📋

- **Translate Only the Values:** Do not modify the keys. For example, `"ButtonShow": "Anzeigen"`.
- **Consistency:** Ensure consistent terminology and grammar throughout the translation.
- **Encoding:** Save the file in **UTF-8** encoding.
- **Proofread:** Double-check for typos and accuracy.
- **Notes:** If there are any ambiguous strings, include a note in your pull request for clarification.

## Get Recognized! 🏅

By contributing to the translations, your GitHub profile will be credited in the Contributors section of the project README. Help us make this application accessible to everyone!

## Need Help?

If you have any questions or need clarification, feel free to [open an issue](https://github.com/YourUsername/Discord-Friend-Manager/issues) or reach out directly. Thank you for your contribution! 🙏

---

*Happy Translating! 🌟*
