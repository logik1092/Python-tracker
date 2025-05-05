# Python Version Tracker Pro

Python Version Tracker Pro automates version management in Python projects. It scans files for VERSION tags, detects missing/outdated versions, inserts tags correctly, creates backups, maintains history, and enables version comparisons. Perfect for teams and individuals seeking consistent versioning with minimal effort.

![Python Version Tracker Pro Screenshot](app_screenshot.png)

## Features

- **Automatic File Scanning**: Monitors Python files for VERSION tags in real-time
- **Smart VERSION Tag Detection**: Identifies files with missing or outdated version tags
- **Intelligent Tag Placement**: Inserts VERSION tags in the correct location in your code
- **Version History**: Maintains a complete history of all version changes
- **File Comparison**: Built-in tools to compare different versions of the same file
- **Automatic Backups**: Creates backups before making any changes to your files
- **Custom Scan Settings**: Configure scan intervals and file filters
- **System Tray Integration**: Minimize to system tray for background monitoring
- **AI Helper Prompt**: Copy a standardized prompt to get AI help with versioning

## Installation

1. Ensure you have Python 3.8+ installed
2. Download the Python Version Tracker Pro package
3. Extract all files to a directory of your choice
4. Run `main.py` to start the application

```bash
python main.py
```

## Usage

### Getting Started

1. Start the application by running `main.py`
2. Click "Select Folder" to choose the Python project directory you want to track
3. The application will scan all Python files in the directory and display their VERSION tag status
4. Files with VERSION tags will be shown with a green "Has TAG" status
5. Files without VERSION tags will be shown with a yellow "Missing TAG" status

### Configuring Settings

- **Scan Interval**: Set how often (in seconds) the application scans for changes
- **File Filters**: Specify file patterns to exclude from monitoring
- **Auto-fix**: Enable automatic fixing of missing VERSION tags
- **Backup Files**: Create backups before modifying files with new VERSION tags
- **System Tray**: Minimize to system tray instead of closing when clicking X
- **Auto-start Tracking**: Automatically start tracking when the application launches

### Working with Files

- **Double-click** on a file to open it in your default editor
- **Right-click** on a file for additional options:
  - Add/Update VERSION Tag
  - Remove VERSION Tag
  - Open File
  - Show File Location
  - Copy Path

### Version History

1. Switch to the "Version History" tab to view the history of version changes
2. Select a file to see all its recorded versions
3. Select a version to view, restore, or compare it with another version

## VERSION Tag Format

Python Version Tracker Pro follows a standard VERSION tag format:

```python
VERSION = "1.0.0"
```

The tag should be placed in a specific order to ensure compatibility:

1. AFTER any shebang (e.g., `#!/usr/bin/python3`)
2. AFTER any encoding declaration (e.g., `# -*- coding: utf-8 -*-`)
3. AFTER any module-level docstring (triple quotes)
4. AFTER any `from __future__ import ...` statements
5. BEFORE the first main import statement or function/class definition

## Troubleshooting

- **Files not showing**: Check if they are excluded in the file filters
- **VERSION tags not detected**: Ensure they follow the standard format `VERSION = "X.Y.Z"`
- **Application won't start**: Make sure all required files are in the same directory
- **Error opening files**: Verify file permissions and that they exist at the specified location

## Support and Contribution

For support, feature requests, or to report bugs, please open an issue on our repository.

Donations are accepted via CashApp @ $logik109

## License

Python Version Tracker Pro is provided as-is with no warranty. All rights reserved.

---

© 2025 Python Version Tracker Pro
