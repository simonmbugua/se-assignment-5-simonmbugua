[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287101&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Prerequisites:
System Requirements: Ensure your system meets the minimum requirements for running VS Code.

Operating System: Windows 11 (64-bit)
Processor: 1.6 GHz or faster processor
Memory: 1 GB RAM
Disk space: 200 MB of available hard disk space
Internet Connection: You need an active internet connection to download the installation package.

Steps to Install Visual Studio Code on Windows 11:
Download Visual Studio Code:

Open your web browser and go to the official Visual Studio Code website: https://code.visualstudio.com/
Click on the "Download for Windows" button. This will download the latest stable version of VS Code.
Run the Installer:

Once the download is complete, locate the downloaded installer file (usually named something like VSCodeSetup-x64-{version}.exe).
Double-click on the installer file to start the installation process.
Install Visual Studio Code:

The VS Code Setup Wizard will open. Click on "Next" to begin.
Choose Destination Location:

By default, VS Code will install in C:\Program Files\Microsoft VS Code. You can change this location if needed by clicking on "Browse...". Click "Next" when ready.
Select Start Menu Folder:

Choose the folder where you want the VS Code shortcuts to be created in the Start menu. Click "Next".
Select Additional Tasks:

Optionally, you can choose to add shortcuts to the desktop and/or to the context menu for easier access. Select the desired options and click "Next".
Install:

Review the installation settings and click on "Install" to begin the installation process.
Complete the Installation:

Wait for the installer to finish installing Visual Studio Code on your system. This usually takes a few moments.
Launch Visual Studio Code:

Once the installation is complete, you can leave the "Launch Visual Studio Code" checkbox checked and click "Finish". Alternatively, you can launch VS Code later from the Start menu or desktop shortcut.
Setup Visual Studio Code (Optional):

Upon launching VS Code for the first time, you may be prompted to install recommended extensions or customize your settings. Follow the prompts as needed.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   1. Settings and Preferences:
Font and Theme:

Navigate to File > Preferences > Settings (or use Ctrl + ,).
Choose a comfortable font and theme under the Text Editor section. Popular themes include "Dark+", "Light+", and various community themes.
Editor Preferences:

Adjust tab size, indentation, line height, and word wrap preferences under Text Editor > Formatting.
File Associations:

Set default file associations for specific languages or file types to enable syntax highlighting and IntelliSense.
2. Extensions:
Extensions are crucial for extending the functionality of VS Code. Here are some essential extensions to consider:

Language Support:

Programming Language Extensions: Install extensions for the programming languages you use (e.g., Python, JavaScript, Java).
Debugger for Chrome: If web development is your focus, this extension allows debugging of JavaScript code in the Chrome browser.
Productivity:

GitLens: Enhances Git integration, providing valuable insights into code repositories directly within VS Code.
Bracket Pair Colorizer: Helps visually match brackets with colors to improve code readability.
Code Spell Checker: Checks spelling in your comments and strings.
Appearance:

Material Icon Theme: Adds colorful icons to files and folders for easier navigation.
Custom CSS and JS Loader: Allows customization of VS Code's appearance through custom CSS and JavaScript.
3. Integrated Terminal:
Shell Selection: Customize the integrated terminal shell to your preferred one (e.g., Command Prompt, PowerShell, Git Bash).
4. Keybindings:
Custom Keybindings: Modify keybindings under File > Preferences > Keyboard Shortcuts to match your workflow or to use shortcuts from other IDEs.
5. User and Workspace Settings:
Workspace Settings: Use workspace-specific settings (settings.json in your workspace folder) to override global settings for specific projects.
6. Version Control:
Initialize Git Repository: If working on a new project, initialize a Git repository (git init) and link it with VS Code for seamless version control integration.
7. User Experience:
Telemetry: Decide whether to enable or disable telemetry reporting under File > Preferences > Settings > Telemetry.
8. Extensions Marketplace:
Regularly explore the Extensions Marketplace (Ctrl + Shift + X) for new extensions and updates to existing ones that could improve your workflow.
Example Configuration (settings.json):
json
Copy code
{
    "editor.tabSize": 2,
    "editor.detectIndentation": true,
    "editor.wordWrap": "on",
    "files.autoSave": "afterDelay",
    "git.autofetch": true,
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Dark+"
}
Adjust these settings based on your preferences and the requirements of your projects. Regularly review and update these configurations to ensure your coding environment remains optimized.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   1. Activity Bar:
Purpose: The Activity Bar is located on the far left side of the VS Code window. It provides quick access to different views and tools within VS Code.

Components:

Explorer: Allows navigation through files and folders in your project.
Search: Provides tools for searching across files.
Source Control: Integrates with version control systems like Git for managing source code changes.
Run and Debug: Offers features for running and debugging applications.
Extensions: Manages VS Code extensions, allowing you to search, install, and manage extensions.
2. Side Bar:
Purpose: The Side Bar is located next to the Activity Bar and contains various panels that provide contextual information and tools related to your current activity or file.

Components:

Explorer: Shows the file system structure of your project and allows you to navigate, open, and manage files and folders.
Search: Provides a search functionality to find text across files in your project.
Source Control: Displays information about the current state of your Git repository and allows you to perform version control operations.
Extensions: Lists installed extensions and provides options to search for new extensions in the VS Code marketplace.
Debug: Provides debugging tools and information when debugging your application.
Remote Explorer (if enabled): Allows you to connect to remote servers or containers and browse their file systems.
3. Editor Group:
Purpose: The Editor Group consists of one or more editors where you can view and edit files. Each editor tab represents an open file or a preview.

Features:

Tabbed Interface: Allows you to have multiple files open simultaneously in different tabs.
Split View: Supports splitting the editor into multiple panes horizontally or vertically to view different parts of the same file or different files.
4. Status Bar:
Purpose: The Status Bar is located at the bottom of the VS Code window and provides information about the current state of your project and the editor.

Components:

Language Mode: Displays the current programming language mode of the active file.
Git Branch: Shows the current Git branch and provides shortcuts to perform Git operations.
Errors and Warnings: Indicates any errors or warnings in the current file.
Line Endings: Displays the current line endings format (e.g., CRLF, LF).
Encoding: Shows the encoding format of the active file.
Spaces/Tab Size: Allows quick adjustment of indentation settings.
Additional Components:
Title Bar: Located at the very top of the VS Code window, it shows the name of the current project and provides window management options (e.g., minimize, maximize, close).

Breadcrumbs: Located above the editor, it provides a navigational trail showing your current location within the file's structure. It can be used to quickly navigate between different parts of the file.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   
   The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows users to execute various commands, perform tasks, and navigate through the editor interface using a command-driven approach. It is particularly useful for accessing features and functionalities quickly without needing to remember specific keyboard shortcuts or navigate through menus.

Accessing the Command Palette:
To access the Command Palette in VS Code, you can use the following methods:

Keyboard Shortcut: Press Ctrl + Shift + P (Windows, Linux) or Cmd + Shift + P (macOS).

Menu Option: Click on View in the top menu bar, then select Command Palette.

Once opened, the Command Palette displays a text input field where you can type commands, and it also provides suggestions based on your input and the context of your workspace.

Examples of Common Tasks Using the Command Palette:
Opening Files:

Type "File: Open File" to open a specific file in your workspace.
Type "File: Open Folder" to open a folder in VS Code.
Searching:

Type "Search: Find" to open the search panel for finding text within files.
Type "Search: Replace" to open the replace panel for performing text replacements.
Version Control (Git):

Type "Git: Pull" to pull changes from a remote repository.
Type "Git: Commit" to commit changes to the local repository.
Type "Git: Push" to push committed changes to a remote repository.
Debugging:

Type "Debug: Start Debugging" to start debugging your application.
Type "Debug: Stop Debugging" to stop the current debugging session.
Tasks:

Type "Tasks: Run Task" to run a predefined task from the tasks.json file.
Type "Tasks: Configure Task" to configure tasks for your project.
Extensions:

Type "Extensions: Install Extensions" to search and install extensions from the VS Code Marketplace.
Type "Extensions: Show Installed Extensions" to view and manage installed extensions.
Settings:

Type "Preferences: Open Settings (JSON)" to directly edit the settings.json file.
Type "Preferences: Open Keyboard Shortcuts" to customize keyboard shortcuts.
Navigation:

Type "Go to File..." to quickly navigate to a specific file in your workspace.
Type "Go to Symbol..." to navigate to a symbol (function, variable, etc.) within the current file.
Editor Layout:

Type "View: Toggle Editor Group Layout" to toggle between different editor layout configurations (e.g., horizontal split, vertical split).
Workspace Management:

Type "Workspaces: Save Workspace As..." to save the current workspace configuration.
Type "Workspaces: Add Folder to Workspace..." to add a folder to the current workspace.
Customizing and Extending:
You can extend the functionality of VS Code by installing extensions, which often add new commands that can be accessed via the Command Palette.
The Command Palette adapts to the context of your workspace and suggests relevant commands based on the files you are working with and the extensions you have installed.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   
   Extensions in Visual Studio Code (VS Code) play a crucial role in enhancing its functionality and customizing the editor to suit specific programming needs and workflows. They are third-party plugins that extend the core capabilities of VS Code, adding features such as language support, debugging tools, productivity enhancements, and integration with external services.

Role of Extensions:
Enhanced Functionality: Extensions provide additional features beyond what comes built-in with VS Code, tailored to different programming languages, frameworks, and development workflows.

Customization: Users can personalize their coding experience by installing extensions that match their preferences and requirements.

Productivity: Extensions automate repetitive tasks, improve code quality through linting and formatting, and integrate with version control systems and build tools.

Finding, Installing, and Managing Extensions:
Finding Extensions:
VS Code Marketplace: The primary source for extensions is the Visual Studio Code Marketplace, accessible through the VS Code editor or directly via web browsers.
Search: Use keywords related to your needs (e.g., "Python", "React", "Git") to find relevant extensions.
Installing Extensions:
Using the Command Palette:

Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
Type "Extensions: Install Extensions".
Search for the extension by name and click "Install".
Via the Extensions View:

Click on the Extensions icon in the Activity Bar.
Search for an extension in the Marketplace tab.
Click on "Install" next to the extension you want to install.
Managing Extensions:
Disabling or Uninstalling:

In the Extensions view (Ctrl + Shift + X), click on the gear icon next to an installed extension.
Choose "Disable" to temporarily disable an extension or "Uninstall" to remove it completely.
Updating:

Extensions that have updates available will show an "Update" button in the Extensions view. Click on it to update to the latest version.
Examples of Essential Extensions for Web Development:
ESLint:

Purpose: Provides ESLint integration for JavaScript and TypeScript projects, helping maintain code quality and adherence to coding standards.
Usage: Highlights errors and warnings in your code, with customizable rules and automatic fixes.
Installation: Search for "ESLint" in the VS Code Marketplace.
Prettier - Code formatter:

Purpose: Automatically formats code to maintain consistent style across your project.
Usage: Integrates with various languages and frameworks like JavaScript, TypeScript, CSS, and JSON.
Installation: Search for "Prettier - Code formatter" in the VS Code Marketplace.
Live Server:

Purpose: Launches a development local server with live reload capability for static and dynamic pages.
Usage: Great for front-end web development to see changes in real-time without manually refreshing the browser.
Installation: Search for "Live Server" in the VS Code Marketplace.
Debugger for Chrome:

Purpose: Enables debugging of JavaScript code in the Google Chrome browser directly from VS Code.
Usage: Set breakpoints, inspect variables, and step through code for better debugging experience.
Installation: Search for "Debugger for Chrome" in the VS Code Marketplace.
Auto Rename Tag:

Purpose: Automatically renames paired HTML/XML tags when one tag is renamed.
Usage: Saves time by keeping your HTML/XML markup consistent and error-free.
Installation: Search for "Auto Rename Tag" in the VS Code Marketplace.
GitLens:

Purpose: Supercharges the Git capabilities built into VS Code by adding detailed information and powerful workflows.
Usage: Visualizes code authorship and changes over time, integrates with issue trackers, and more.
Installation: Search for "GitLens" in the VS Code Marketplace.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   Opening and using the integrated terminal in Visual Studio Code (VS Code) is straightforward and offers several advantages over using an external terminal. Here’s how you can open and utilize the integrated terminal:

Opening the Integrated Terminal:
Using the Menu:

Click on Terminal in the top menu bar.
Select New Terminal.
Using Keyboard Shortcut:

Press Ctrl + (backtick key) on Windows and Linux.
Press Cmd + (backtick key) on macOS.
Using the Command Palette:

Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
Type "View: Toggle Integrated Terminal" and press Enter.
Using the Integrated Terminal:
Once the integrated terminal is open:

Navigation: Navigate to your project directory using standard shell commands (cd, ls, etc.).

Running Commands: Execute commands directly within the integrated terminal (e.g., start a development server, run build scripts, execute Git commands).

Customization: You can customize the terminal shell used by VS Code (e.g., PowerShell, Command Prompt, Git Bash) through VS Code settings.

Integration: The integrated terminal shares the same workspace as the editor, allowing seamless interaction between editing code and executing commands.

Advantages of Using the Integrated Terminal:
Contextual Awareness:

The integrated terminal operates within the same workspace context as your code, making it easier to switch between editing and command-line tasks without losing context.
Efficiency:

Avoids the need to switch between multiple applications or windows. Everything is contained within VS Code, reducing clutter and streamlining workflows.
Integration with VS Code Features:

Terminal commands can interact with VS Code’s built-in features and extensions, enhancing productivity (e.g., running tasks defined in tasks.json, integrating with version control).
Customization:

You can customize the terminal appearance and behavior through VS Code settings and extensions, tailoring it to match your preferences and workflow.
Debugging Integration:

Debugging output and console messages from your applications can be viewed directly in the integrated terminal, providing a consolidated view of development activity.
Cross-Platform Consistency:

Works consistently across different operating systems (Windows, macOS, Linux), unlike external terminals which may have different behaviors or features.
External Terminal Considerations:
While the integrated terminal offers many advantages, there are scenarios where an external terminal might still be preferred, such as when working with specialized environments or tools that require specific terminal features not supported by VS Code’s integrated terminal.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   
   In Visual Studio Code (VS Code), managing files and folders is essential for organizing your projects and navigating through different files efficiently. Here’s a guide on how to create, open, and manage files and folders, as well as how to navigate between them effectively:

Creating and Opening Files and Folders:
Creating a New File:

Click on the Explorer icon in the Activity Bar on the left (folder icon).
Right-click on the folder where you want to create the new file.
Select New File from the context menu and enter the desired filename.
Creating a New Folder:

Similarly, right-click on the parent folder in the Explorer.
Select New Folder and enter the name of the new folder.
Opening Files:

Double-click on a file in the Explorer to open it in the editor.
Alternatively, use the File > Open File... menu option or Ctrl + O (Cmd + O on macOS) and navigate to the file you want to open.
Opening Folders:

Use File > Open Folder... to open an entire folder in VS Code.
Alternatively, drag and drop a folder into the VS Code window to open it.
Managing Files and Folders:
Renaming Files and Folders:

Right-click on a file or folder in the Explorer.
Select Rename from the context menu and enter the new name.
Deleting Files and Folders:

Right-click on a file or folder in the Explorer.
Select Delete from the context menu to move it to the Recycle Bin (Windows) or Trash (macOS).
Moving Files and Folders:

Drag and drop files and folders within the Explorer to rearrange them.
You can also cut (Ctrl + X or Cmd + X) and paste (Ctrl + V or Cmd + V) files/folders within the Explorer to move them.
Navigating Between Files and Directories Efficiently:
Using the Explorer:

The Explorer in the Activity Bar allows you to navigate through files and folders in your workspace. Double-click folders to expand them and view their contents.
Using the Breadcrumbs:

Located at the top of the editor, breadcrumbs provide a trail of your current location within the file hierarchy. You can click on different parts of the breadcrumb trail to navigate up or sideways in the directory structure.
Switching Between Open Files:

Use Ctrl + Tab (Windows/Linux) or Cmd + Tab (macOS) to cycle through open files in the editor.
Use Ctrl + P (Windows/Linux) or Cmd + P (macOS) to open the Quick Open menu and type the name of the file you want to open.
Navigating to Symbols:

Use Ctrl + Shift + O (Windows/Linux) or Cmd + Shift + O (macOS) to open the Quick Outline menu. This allows you to quickly navigate to functions, classes, or other symbols within the current file.
Go to Definition:

Use F12 to jump directly to the definition of a function or variable (if supported by the language extension).
Integrated Search:

Use Ctrl + Shift + F (Windows/Linux) or Cmd + Shift + F (macOS) to search across all files in the workspace. Use Ctrl + F (Windows/Linux) or Cmd + F (macOS) for searching within the current file.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   
   In Visual Studio Code (VS Code), users can find and customize settings through the settings interface or by directly editing the settings.json file. Here’s how you can access and customize settings for changing the theme, font size, and keybindings:

Finding and Customizing Settings:
Accessing Settings:

Open VS Code.
Click on the gear icon (⚙️) in the bottom left corner of the Activity Bar to open the Settings tab.
Alternatively, use the keyboard shortcut Ctrl + , (Windows/Linux) or Cmd + , (macOS) to open the Settings tab directly.
Search for Settings:

In the Settings tab, you can search for specific settings using the search bar at the top.
Type keywords such as "theme", "font", "keybindings" to find relevant settings.
Editing settings.json:

Click on the {} icon in the top right corner of the Settings tab to open the settings.json file.
Directly edit JSON settings in this file. Changes made here override default and user-specific settings.
Examples of Customizations:
Changing the Theme:
From Settings Interface:

Search for "Color Theme" in the Settings tab.
Click on the dropdown menu under Workbench › Color Theme and select the desired theme (e.g., "Dark+", "Light+", a custom theme).
Editing settings.json:

Add or modify the following JSON setting:
json
Copy code
"workbench.colorTheme": "Dark+"
Replace "Dark+" with the name of your preferred theme.
Adjusting Font Size:
From Settings Interface:

Search for "Font Size" in the Settings tab.
Adjust the Editor: Font Size setting to your preferred size (e.g., 14).
VS Code supports both pixel (px) and point (pt) units for font sizes.
Editing settings.json:

Add or modify the following JSON setting:
json
Copy code
"editor.fontSize": 14
Adjust the number (14 in this example) to your desired font size.
Customizing Keybindings:
From Settings Interface:

Search for "Keybindings" in the Settings tab.
Click on Open Keyboard Shortcuts to open the keybindings settings.
You can modify existing keybindings or add custom keybindings here.
Editing keybindings.json (Advanced):

Click on the {} icon in the top right corner of the Keyboard Shortcuts tab to open keybindings.json.
Add or modify JSON entries to define custom keybindings. For example:
json
Copy code
[
    {
        "key": "ctrl+shift+l",
        "command": "editor.action.insertLineAfter",
        "when": "editorTextFocus"
    }
]
This example binds Ctrl + Shift + L to insert a line after the current line in the editor.   

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Setting up and starting debugging in VS Code involves a few straightforward steps. Here’s a concise outline to guide you through the process:

Steps to Set Up and Start Debugging in VS Code:
Install Necessary Extensions:

Ensure you have the necessary extensions installed in VS Code for the programming language you are using (e.g., Python, JavaScript).
Open Your Project:

Open VS Code and navigate to the folder or workspace where your project files are located.
Create a Launch Configuration:

VS Code uses launch configurations (in a launch.json file) to determine how to start and debug your program. You can create this file manually or let VS Code generate it for you.

To generate a launch configuration:

Click on the debug icon in the Activity Bar on the side (or use the keyboard shortcut Ctrl+Shift+D).
Click on the gear icon (⚙️) to create a launch.json file and select the environment relevant to your project (e.g., Node.js, Python).
Set Breakpoints:

In your source code files, set breakpoints by clicking in the gutter next to the line number where you want execution to pause.
Start Debugging:

Press F5 or click the green play button next to the configurations dropdown in the Debug view.
Debugging Controls:

Once debugging starts, you can use the following controls from the Debug toolbar:
Step Over (F10): Execute the current line of code and move to the next one.
Step Into (F11): Step into the function call, if possible.
Step Out (Shift+F11): Finish executing the current function and return to the caller.
Continue (F5): Resume execution until the next breakpoint.
Restart (Ctrl+Shift+F5): Restart the debugging session.
Stop (Shift+F5): Stop debugging.
Inspect Variables and Call Stack:

While debugging, you can inspect variables and the call stack to understand the state of your program at any given point.
Debug Console:

Use the Debug Console to directly execute expressions and commands during debugging.
Key Debugging Features in VS Code:
Multi-language Support: VS Code supports debugging for a wide range of programming languages including JavaScript, TypeScript, Python, C++, and more.

IntelliSense: Provides context-aware suggestions as you debug, helping you quickly navigate and explore code.

Watch Expressions: Allows you to monitor the value of variables or expressions in real-time as you step through code.

Conditional Breakpoints: Set breakpoints that only pause execution when a certain condition is met, enhancing flexibility in debugging.

Task Automation: Integrate debugging with tasks and build processes, enabling automated debugging workflows.

Remote Debugging: Debug applications running on remote machines or containers, useful for development scenarios involving servers or IoT devices.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    
    Integrating Git with VS Code for version control is straightforward and can greatly streamline your development workflow. Here’s a step-by-step guide to help you get started with Git in VS Code, from initializing a repository to pushing changes to GitHub:

Initializing a Repository:
Open VS Code and Open Your Project:

Launch VS Code and open the folder or workspace where your project files are located.
Initialize Git Repository:

Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
Type and select "Git: Initialize Repository" and choose the root folder of your project.
Alternatively, you can initialize a repository using Git commands in the integrated terminal:
bash
Copy code
git init
Making Commits:
Stage Changes:

In VS Code, use the Source Control view (Ctrl+Shift+G) to see changes.
Click on the + icon next to each file or use the + button at the top to stage changes for commit.
Commit Changes:

Enter a commit message that describes the changes you are committing.
Press Ctrl+Enter or click the checkmark icon to commit the changes.
Pushing Changes to GitHub:
Create a GitHub Repository (if not already created):

Go to GitHub and create a new repository. Note down the repository URL (e.g., https://github.com/username/repository.git).
Add Remote Repository:

In VS Code, open the Command Palette and select "Git: Add Remote".
Enter a name for the remote (e.g., origin) and paste the GitHub repository URL when prompted.
Push Commits:

After committing your changes locally, you can push them to GitHub.
Open the Command Palette and select "Git: Push".
Choose the remote repository (origin in most cases) to push your changes to GitHub.
Additional Tips:
Pull Changes: Before pushing changes, ensure you pull any changes from the remote repository (Git: Pull from the Command Palette) to avoid conflicts.

Branch Management: Use the Source Control view to create and switch branches (Git: Create Branch, Git: Checkout to...).

Resolve Conflicts: If conflicts arise during pulls or merges, VS Code provides tools to help resolve them visually.

Extensions: Consider installing Git-related extensions like GitLens for enhanced visualization and history exploration.


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

