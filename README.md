# AutoFileSort

**AutoFileSort** is a lightweight automation tool designed to keep your workspace clean. It monitors specific folders (like your Downloads or Desktop) and instantly moves incoming files into organized subfolders based on their file extensions.

[Download Latest Release](https://github.com/nthnerr/AutoFileSort/releases)

---

## Why use AutoFileSort?

* **No More Manual Sorting:** Stop spending time dragging files into folders. Let the script handle it the second a file is saved.
* **Instant Organization:** Replaces the messy "Downloads" folder with a structured system (e.g., .pdf goes to Documents, .jpg goes to Images).
* **Set and Forget:** Runs in the background so your desktop stays clean without any manual effort.
* **Customizable Logic:** Easily define which file types go to which destination.

## Installation

1. **Download** the latest version of AutoFileSort.
2. **Configure** your directory paths in the provided config file to tell the script which folders to watch.
3. **Run** the script to begin monitoring your files.

## How to Use

1. Start the application.
2. The system will enter **MONITORING** mode.
3. Any file added to your "Watch" folder will be automatically moved to its designated category.
4. Check the logs or status window to see real-time sorting activity.

## Technical Specs
* **Logic:** Extension-based sorting (Regex/String matching).
* **Performance:** Low-latency file system monitoring.
* **Platform:** Optimized for Windows and macOS.

---
*Created by [nthnerr](https://github.com/nthnerr)*
