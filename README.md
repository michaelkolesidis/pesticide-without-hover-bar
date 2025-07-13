# Pesticide (without hover bar) - Manifest V3

![Pesticide logo](./icon_128.png)

**Pesticide** is a Chrome extension designed to help you visualize the layout and structure of any webpage by outlining every HTML element. It’s a powerful tool for debugging CSS and understanding how elements are nested on the page.

When activated, Pesticide injects custom CSS into the current tab, applying colored outlines to all elements based on their type. This makes it easy to identify spacing, nesting, and potential layout issues at a glance.

## ✨ Features

✅ One-click toggle to enable or disable visual outlines without needing page reload
🎨 Faithfully reflects the original website's CSS — no hover effects, no color changes, no shadows.
🌍 Works on any website
🔐 Built using Manifest V3 for enhanced security and performance
🚫 No interference with site functionality or user interactions

## 🚀 How to use

1. Install the extension from the Chrome Web Store or load it unpacked
2. Click the Pesticide icon in your toolbar to toggle element outlines
3. Click again to turn them off

## 📥 Installation

### From Chrome Web Store

Search for "Pesticide (without hover bar)" on the Chrome Web Store and install.

### Manual Installation

1. Download and extract this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked" and select the extracted folder

## 🔄 Changes in Manifest V3 version

This version has been updated to use Manifest V3, which includes:

- Using a service worker instead of a background page
- More secure permission model with only necessary permissions
- Using chrome.action instead of browserAction
- Using chrome.scripting API for content script injection

## 🙏 Acknowledgements

The original *Pesticide CSS* by created by Adam Morse (mrmrs).

The extension and its predecesors (this one is forked ) has been maintanined and coded by
Bailey Hadden
Paul Molluzzo

This extension is built upon the original Pesticide CSS created by Adam Morse (mrmrs).

This version is a fork of earlier extensions that have been maintained and developed by
Bailey Hadden and Paul Molluzzo.

## 📜 License

<a href="https://www.gnu.org/licenses/agpl-3.0.html"><img src="./images/agplv3.svg" height="80px" /></a>

Copyright (c) Michael Kolesidis  
The code is licensed under the [GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.html).  
