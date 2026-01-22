---
layout: "default"
title: "🎉 vim-rosetta - Translate Your Code with Ease"
description: "🌍 Translate code comments and variable names easily with vim-rosetta, a Vim plugin that integrates Google Translate for seamless multilingual coding."
---
# 🎉 vim-rosetta - Translate Your Code with Ease

## 🚀 Getting Started
Welcome to vim-rosetta! This Vim plugin helps you translate comments and variable names using the Google Translate API. With features like asynchronous translations, popup displays, and multi-format name completion, coding becomes smoother and more intuitive.

## 📥 Download vim-rosetta
[![Download vim-rosetta](https://img.shields.io/badge/Download-vim--rosetta-brightgreen)](https://github.com/eklasajal/vim-rosetta/releases)

To get started, first visit the [Releases page](https://github.com/eklasajal/vim-rosetta/releases) to download the latest version of vim-rosetta.

## 📋 Features
- **Seamless Translation**: Automatically translate comments and variable names right in your editor.
- **Asynchronous Processing**: Experience smooth functionality without delays.
- **Popup Display**: Get translations in a user-friendly popup.
- **Multi-Format Support**: Work with various identifier formats with ease.

## 🛠️ System Requirements
- **Vim Version**: Ensure you are using Vim version 8.0 or higher.
- **Operating System**: This plugin works on Windows, macOS, and Linux.
- **Internet Connection**: A stable internet connection is needed to access Google Translate.

## 💾 Installation Steps
1. **Download the Plugin**:
   - Visit the [Releases page](https://github.com/eklasajal/vim-rosetta/releases).
   - Select the latest version and download the appropriate file for your system.

2. **Extract and Install**:
   - If the downloaded file is compressed (e.g., .zip or .tar.gz), extract it to your preferred location.
   - Move the extracted files to your Vim plugin directory:
     - For example, on macOS/Linux, move the files to `~/.vim/pack/vendor/start/`
     - On Windows, place them in `%USERPROFILE%/vimfiles/pack/vendor/start/`

3. **Configure Your API Key**:
   - You need to have a Google Cloud account.
   - Follow Google’s documentation to set up the Google Translate API.
   - Copy your API key and open your Vim configuration file (usually `~/.vimrc` on macOS/Linux or `_vimrc` on Windows).
   - Add the following line to set your API key:
     ```vim
     let g:vim_rosetta_api_key = "YOUR_API_KEY_HERE"
     ```

4. **Start Using vim-rosetta**:
   - Open Vim and load a file containing comments or variable names.
   - Use the designated command to trigger translations.
   - Enjoy an effortless coding experience with real-time translations.

## ⚙️ Usage Instructions
Once you have installed vim-rosetta, you can start using it as follows:

1. **Triggering Translations**:
   - Use the command `:RosettaTranslate` while your cursor is over a comment or variable name.
   - You will see the translated text pop up in a notification box.

2. **Multi-lingual Support**:
   - The plugin supports many languages. To change the target language, update your configuration file by adding:
     ```vim
     let g:vim_rosetta_target_language = "LANGUAGE_CODE"
     ```
   - Replace `LANGUAGE_CODE` with the desired language code (e.g., `es` for Spanish, `fr` for French).

3. **Troubleshooting**:
   - Ensure your API key is valid and active.
   - Check your internet connection if translations are not showing.

## 📖 Additional Documentation
For more detailed information about configuring and using vim-rosetta, please refer to the [Wiki](https://github.com/eklasajal/vim-rosetta/wiki). Here you will find examples, FAQs, and more tips to maximize your experience with the plugin.

## 📫 Support
If you encounter issues or have questions, please open an issue in the [GitHub Issues section](https://github.com/eklasajal/vim-rosetta/issues). Our community is here to help you. 

## 🔗 Useful Links
- [Releases Page](https://github.com/eklasajal/vim-rosetta/releases)
- [Wiki](https://github.com/eklasajal/vim-rosetta/wiki)
- [Contribution Guide](https://github.com/eklasajal/vim-rosetta/blob/main/CONTRIBUTING.md)

Thank you for using vim-rosetta! We hope it enhances your coding experience.