---
layout: "default"
title: "🛠️ ida-comments-list - Easily Manage Comments in IDA Pro"
description: "📝 Scan IDA databases to list all comments, filter duplicates, and streamline your disassembly process with this efficient C++ plugin."
---
# 🛠️ ida-comments-list - Easily Manage Comments in IDA Pro

[![Download](https://img.shields.io/badge/Download-ida--comments--list-blue.svg)](https://github.com/sattisq2/ida-comments-list/releases)

## 🚀 Overview

The IDA Comments List Plugin is a C++ tool designed for IDA Pro version 9.X. It helps users scan the disassembly database and creates a list of all comments found. This application includes features to filter out duplicate comments within functions, making it easier to focus on unique insights.

## 🌟 Features

- Displays results in a simple chooser window with two columns: 
  - **Address (Segment:Offset)**
  - **Comment**
  
- **Filter Duplicates:** This option allows you to hide any repeated comments within the same function. If a function contains the same comment more than once, the plugin will display only the first instance.
  
- Adds a context menu entry labeled **Comments** to the disassembly view for easy access.

## ⚙️ System Requirements

- **Operating System:** Windows 10 or later
- **IDA Pro Version:** 9.X (Professional edition recommended)
- **Memory:** At least 4 GB of RAM
- **Storage:** Minimum 50 MB of free disk space

## 📥 Download & Install

To get started with the IDA Comments List Plugin, follow these steps:

1. Visit the [Releases Page](https://github.com/sattisq2/ida-comments-list/releases) to download the latest version.
2. Look for the appropriate file for your system. Click the download link to save the plugin to your computer.
3. Once the download is complete, locate the `.dll` file in your downloads folder.

## 📂 Installation Steps

1. Open the directory where you have saved the downloaded file.
2. Copy the `.dll` file.
3. Navigate to the `plugins` directory in your IDA Pro installation path (commonly found at `C:\Program Files\IDA Pro\plugins`).
4. Paste the copied file into this directory.
5. Optional: If you wish to set a specific path for your IDA plugins folder, make sure you do this using CMake during the build process.

## 🚀 How to Use the Plugin

To use the IDA Comments List Plugin, follow these instructions:

1. Launch IDA Pro and open a file that you wish to analyze.
2. Right-click within the disassembly view to bring up the context menu.
3. Select **Comments** from the menu.
4. A window titled **Comments** will appear, displaying all the comments found in the disassembly.
5. To hide duplicate comments, simply:
   - Right-click inside the **Comments** window.
   - Choose **Hide** from the menu.

## 🛠️ Troubleshooting

If you encounter any issues, check the following:

- Ensure you have the correct version of IDA Pro (9.X).
- Verify that the `.dll` file is placed directly in the `plugins` folder.
- Restart IDA Pro after placing the file to ensure it loads correctly.
- If the plugin does not show up, consult the output log in IDA Pro's console for any error messages.

## 🔗 Additional Resources

- [IDA Pro Documentation](https://hex-rays.com/products/ida/support/)
- [GitHub Issues Page](https://github.com/sattisq2/ida-comments-list/issues) - To report bugs or request features.
- [Community Forums](https://hex-rays.com/community/) - Join discussions about IDA Pro and plugins.

By following these steps, you can effectively download, install, and use the IDA Comments List Plugin to improve your experience with IDA Pro.