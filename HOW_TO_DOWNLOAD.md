# How to Download and Set Up PathTool

**PathTool** is a command-line utility for managing the system PATH environment variable on Windows 10 and 11.

## Steps to Download and Use

1. Go to the [Releases](https://github.com/Mohammedimad4099/PathTool/releases) section of this repository.
2. Choose the version you want to download (for example, `v1.0.0` or `v1.1.0`).
3. Click on the release to open its page.
4. Under **Assets**, download the `.exe` file (e.g., `pathtool.exe` or `pathtool-1.1.0.exe`).
5. Save the `.exe` file to a folder of your choice.

## Initial Setup

Before using PathTool for the first time, you need to run the install command:

```cmd
pathtool.exe -install
`````

This command will:
Create all necessary files for PathTool to work.
Add PathTool integration to the right-click context menu of folders.
Prepare the tool for managing PATH entries.

⚠️ Make sure to run the command in Administrator mode to install.

Usage
After installation, you can use PathTool commands such as:
pathtool.exe -add [path]
pathtool.exe -rm [path or index]
pathtool.exe -s [path or index]
pathtool.exe -edit [old] [new]
pathtool.exe -b
pathtool.exe -b -r

