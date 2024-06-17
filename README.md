[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287364&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - 1.Download VS Code:
Open your web browser and go to the Visual Studio Code download page.
The website should automatically detect your operating system as Windows.
Click on the "Download for Windows" button to download the VS Code installer.
2.Run the Installer:
Once the download is complete, locate the downloaded installer file (usually named something like VSCodeSetup-x64-{version}.exe) in your Downloads folder or the location where you saved it.
Double-click on the installer file to run it.
3.Begin Installation:
The installer will launch, and you will see a welcome screen. Click on the "Next" button to proceed.
4.Accept License Agreement:
Read and accept the License Agreement by checking the box next to "I accept the agreement" and then click "Next."
5.Choose Components:
On the "Select Additional Tasks" screen, you can choose additional components to install along with VS Code, such as adding options to the context menu or creating shortcuts. Customize as desired and click "Next."
6.Select Installation Location:
Choose the destination folder where you want to install VS Code. The default location is usually C:\Program Files\Microsoft VS Code. Click "Next" to continue.
7.Create Start Menu Folder:
Optionally, you can create a Start Menu folder for VS Code shortcuts. Click "Next" after making your selection.
8.Create Desktop Shortcut:
Choose whether you want to create a desktop shortcut for VS Code. Check the box if desired and click "Next."
9.Begin Installation:
Review your selected options on the "Ready to Install" screen. Click "Install" to start the installation process.
10.Complete Installation:
Wait for the installation process to complete. This may take a few moments.
Once the installation finishes, you will see a "Completing the Visual Studio Code Setup Wizard" screen. Ensure the "Launch Visual Studio Code" option is checked and click "Finish."
11.Launch Visual Studio Code:
Visual Studio Code will launch automatically after the installation is complete.
12.Verify Installation:
Once VS Code is open, you can verify that it's installed correctly by checking the version information in the lower-right corner of the window.
Configure Settings: Customize VS Code settings according to your preferences by accessing the Settings menu (File > Preferences > Settings or Ctrl+,).
Install Extensions: Enhance VS Code functionality by installing extensions. Use the Extensions view (View > Extensions or Ctrl+Shift+X) to browse and install extensions from the VS Code Marketplace.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
After installing Visual Studio Code (VS Code) for the first time, several initial configurations and settings adjustments can enhance your coding experience and productivity. 
Initial Configurations:
1.Theme:
Choose a color theme that suits your preference and provides good readability. Some popular themes include "Default Dark+", "Monokai", "Solarized Dark", and "Dracula".
2.Font Settings:
Adjust the font family, size, and line height based on your comfort and readability. Common fonts used in coding are "Consolas", "Fira Code", "Menlo", and "Courier New".
3.Indentation and Formatting:
Set your preferred indentation style (tabs or spaces) and tab size. Configure code formatting settings for languages you frequently work with.
4.Auto Save:
Decide whether you want VS Code to automatically save your changes. Options include "onFocusChange" (save when switching to another window) and "afterDelay" (save after a specific delay).
5.File Associations:
Associate specific file types with the appropriate language mode for syntax highlighting and IntelliSense suggestions.

Important Settings:
1.Editor Settings:
Adjust editor-specific settings such as word wrap, minimap visibility, line numbers, and scroll bar appearance.
2.Extensions Management:
Configure VS Code's extension settings, including auto-update extensions, recommended extensions, and workspace-specific extensions.
3.Integrated Terminal:
Customize the integrated terminal settings, such as the default shell (e.g., PowerShell, Bash), terminal font, cursor style, and terminal behavior.
4.Keyboard Shortcuts:
Familiarize yourself with default keyboard shortcuts and customize them as needed for your workflow. VS Code provides extensive customization options for keyboard shortcuts.

Recommended Extensions:
1.Code Formatting:
Install extensions like "Prettier" or "ESLint" for automatic code formatting and style enforcement.
2.Version Control:
If you're using version control systems like Git, install the "GitLens" extension for enhanced Git integration, code diffs, and repository management.
3.Debugger:
Install language-specific debugging extensions (e.g., "Python", "Java", "JavaScript") for debugging capabilities within VS Code.
4.Productivity Tools:
Consider installing productivity-enhancing extensions such as "Live Server" for web development, "Bracket Pair Colorizer" for improved bracket visualization, and "Path Intellisense" for auto-completion of file paths.
5.Language Support:
Install language support extensions for languages you frequently work with (e.g., "Python", "JavaScript", "Java", "C++") to benefit from language-specific IntelliSense, syntax highlighting, and code snippets.

Workspace Settings:
1.Workspace-specific Settings:
Utilize VS Code's ability to configure settings at the workspace level. This allows you to customize settings specific to each project or workspace.
2.Workspace Recommendations:
VS Code may suggest recommended extensions or settings based on the type of project or workspace you're working on. Consider these recommendations for optimal configurations.

Final Steps:
1.Save Configurations:
Save your configurations and settings changes by clicking on the "Save" button or using the shortcut (Ctrl+S or Cmd+S).
2.Reload Window:
If necessary, reload the VS Code window for settings changes to take effect (Ctrl+Shift+P > "Reload Window").


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
1.Activity Bar:
Purpose: The Activity Bar is located on the far left side of the VS Code window. It provides quick access to different views and functionalities within the editor.
Components:
Explorer: Allows you to navigate and manage files and folders in your workspace.
Search: Provides search functionality across files, folders, and text within your project.
Source Control: Integrates version control systems like Git for managing code changes, commits, and branches.
Debug: Offers debugging tools and configurations for debugging your code.
Extensions: Manages VS Code extensions, allowing you to install, uninstall, and manage extensions.
Remote Explorer: Facilitates remote development and connection to remote servers or containers.

2.Side Bar:
Purpose: The Side Bar complements the Activity Bar by displaying additional information and context-specific panels.
Components:
Explorer: Shows the file and folder structure of your project for easy navigation and management.
Search: Displays search results and provides options for refining search queries.
Source Control: Shows changes, branches, and commit history when working with version control systems like Git.
Debug: Provides debugging controls, breakpoints, and debug configurations.
Extensions: Lists installed extensions and allows access to extension settings and marketplace.

3.Editor Group:
Purpose: The Editor Group is the central area where you edit and work with files, code, and text.
Components:
Tabs: Each open file or editor is represented by a tab in the Editor Group. You can switch between tabs to navigate between files.
Split View: Allows you to split the Editor Group horizontally or vertically to view and edit multiple files simultaneously.
Editor Toolbar: Offers editor-specific actions and commands such as save, undo, redo, and more.
Editor Area: Where you write and edit code, text, or markdown content. Supports syntax highlighting, IntelliSense, and other editor features.

4.Status Bar:
Purpose: The Status Bar is located at the bottom of the VS Code window and provides information, feedback, and quick actions.
Components:
Language Mode Indicator: Displays the current language mode of the active file (e.g., Python, JavaScript, Markdown).
Line and Column Number: Shows the current cursor position in terms of line number and column number.
File Encoding: Indicates the encoding format (e.g., UTF-8) of the active file.
Line Ending: Displays the line ending type (e.g., CRLF, LF) used in the active file.
Editor Settings: Quick access to editor settings such as indentation, line wrap, and language mode.
Git Branch: Shows the active Git branch and provides Git-related actions for version control.



4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
  The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows users to access and execute various commands, settings, and actions within the editor. It provides a convenient way to perform tasks without needing to navigate through menus or remember specific keyboard shortcuts. 
Accessing the Command Palette:
1.Keyboard Shortcut:
Use the keyboard shortcut Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS) to open the Command Palette.
This shortcut works regardless of which view or editor you're currently focused on within VS Code.
2.Menu Option:
Alternatively, you can access the Command Palette from the menu by clicking on View > Command Palette.

Common Tasks with the Command Palette:
1.File Operations:
Open a file: Type "Open File" in the Command Palette and select the desired file from the list.
Save a file: Type "Save" or "Save As" to save the current file or choose a new location for saving.
Close a file: Type "Close" to close the active editor tab.
2.Navigation:
Switch between open files: Type "Switch File" or "Next/Previous Editor" to navigate between open editor tabs.
Go to a specific line: Type "Go to Line" and enter the line number to navigate to that line in the active file.
3.Settings and Preferences:
Open settings: Type "Preferences: Open Settings" to access VS Code's settings and configuration options.
Change color theme: Type "Preferences: Color Theme" to switch between different color themes for the editor.
4.Extensions and Plugins:
Install an extension: Type "Extensions: Install Extensions" to open the Extensions view and search for/install new extensions.
Manage extensions: Type "Extensions: Manage Extensions" to view and manage installed extensions.
5.Debugging:
Start debugging: Type "Debug: Start Debugging" to begin debugging your code using configured debug configurations.
Manage breakpoints: Type "Debug: Toggle Breakpoint" to add or remove breakpoints in your code.
6.Version Control (Git):
Commit changes: Type "Git: Commit" to commit staged changes to your Git repository.
Pull/push changes: Type "Git: Pull" or "Git: Push" to fetch or push changes to/from a remote Git repository.
7.Terminal and Tasks:
Open integrated terminal: Type "Terminal: Create New Integrated Terminal" to open a new terminal window within VS Code.
Run tasks: Type "Tasks: Run Task" to execute predefined tasks or scripts configured in the tasks.json file.
   

6. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
 Extensions play a crucial role in enhancing the functionality and capabilities of Visual Studio Code (VS Code). They allow users to customize their development environment, add new features, and integrate with various tools and technologies. 
Role of Extensions in VS Code:
1.Enhancing Functionality:
Extensions add new features and functionalities to VS Code, such as language support, code formatting, debugging tools, version control integration, and more.
They extend the editor's capabilities beyond its core features, making it a versatile and powerful development environment.
2.Customization:
Users can customize their coding experience by installing extensions that match their programming languages, frameworks, and workflow preferences.
Extensions allow for personalization, allowing users to tailor VS Code to their specific needs and requirements.
3.Integration:
Extensions integrate with external tools, services, and platforms, enabling seamless collaboration, automation, and efficiency in development workflows.
They provide integrations with popular version control systems (e.g., Git), task runners, build tools, code linters, and more.

Finding, Installing, and Managing Extensions:
1.Finding Extensions:
Open the Extensions view in VS Code by clicking on the Extensions icon in the Activity Bar (Ctrl+Shift+X).
Use the search bar to browse for extensions based on categories, keywords, or functionality.
Explore popular extensions, recommended extensions, and trending extensions in the VS Code Marketplace.
2.Installing Extensions:
Click on the extension you want to install, then click the "Install" button.
Wait for the installation process to complete. VS Code will download and install the extension automatically.
3.Managing Extensions:
After installation, extensions can be managed from the Extensions view.
Enable/disable extensions by toggling the switch next to each extension.
Uninstall extensions by clicking the gear icon next to an extension and selecting "Uninstall."

Examples of Essential Extensions for Web Development:
1.HTML CSS Support:
Provides IntelliSense, code completion, and syntax highlighting for HTML, CSS, and embedded CSS within HTML files.
2.JavaScript (ESLint, Prettier):
ESLint: Linter for JavaScript code to enforce coding standards and identify errors.
Prettier: Code formatter for JavaScript, HTML, CSS, and other languages to maintain consistent code style.
3.Debugger for Chrome/Firefox:
Enables debugging of JavaScript code in Chrome or Firefox browsers directly from VS Code.
4.GitLens:
Enhances Git integration with features like inline Git blame annotations, commit history exploration, and repository insights.
5.Live Server:
Launches a local development server with live reload functionality for HTML, CSS, and JavaScript files.
6.Bootstrap, Tailwind CSS IntelliSense:
Provides IntelliSense and autocompletion for Bootstrap and Tailwind CSS classes in HTML and CSS files.
7.REST Client:
Allows sending HTTP requests and testing APIs directly from within VS Code using HTTP request files. 


8. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
Opening the Integrated Terminal:
1.Open the Command Palette:
Use the keyboard shortcut Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS) to open the Command Palette.
2.Access the Integrated Terminal:
In the Command Palette, type "Terminal: Create New Integrated Terminal" and select the option when it appears.
Alternatively, you can directly use the keyboard shortcut `Ctrl+`` (backtick) to toggle the integrated terminal.

Using the Integrated Terminal:
1.Navigation:
Once the integrated terminal is open, you can navigate to different directories using standard terminal commands such as cd (change directory) and ls (list directory contents).
2.Running Commands:
You can run commands directly in the integrated terminal, such as compiling code, running scripts, executing Git commands, and more.
3.Multiple Terminals:
VS Code supports multiple integrated terminals. You can open additional terminals by clicking the + button in the integrated terminal panel or using the Command Palette (Terminal: Create New Integrated Terminal).
4.Customization:
The integrated terminal in VS Code is highly customizable. You can configure the terminal shell (e.g., PowerShell, Bash), terminal font, cursor style, color scheme, and other settings.

Advantages of Using the Integrated Terminal:
1.Seamless Integration:
The integrated terminal is seamlessly integrated into VS Code, allowing you to switch between editing code and running terminal commands within the same window.
2.Workflow Efficiency:
Using the integrated terminal reduces context switching and improves workflow efficiency. You can perform development tasks, run scripts, and manage version control without leaving the editor.
3.Access to VS Code Features:
You can take advantage of VS Code features within the terminal, such as syntax highlighting for commands, IntelliSense for file paths, and keyboard shortcuts for navigation.
4.Workspace Awareness:
The integrated terminal is aware of your workspace settings and configurations, making it easier to set up environment variables, run project-specific commands, and manage dependencies.
5.Debugging Support:
You can integrate debugging tools and debug configurations directly into the integrated terminal, enhancing your debugging experience within VS Code.

9. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
Creating Files and Folders:
1.Create a New File:
Click on the Explorer icon in the Activity Bar or use the keyboard shortcut Ctrl+Shift+N (Windows/Linux) or Cmd+Shift+N (macOS).
Enter a filename when prompted, and the new file will be created in the root directory of your workspace.
2.Create a New Folder:
Right-click within the Explorer panel and select "New Folder."
Enter a folder name, and the new folder will be created in the current directory.

Opening Files and Folders:
1.Open a File:
Double-click on a file in the Explorer panel to open it in the editor.
Alternatively, use the keyboard shortcut Ctrl+O (Windows/Linux) or Cmd+O (macOS) to open a file by browsing through your workspace.
2.Open a Folder:
Click on "File > Open Folder" in the menu bar, or use the keyboard shortcut Ctrl+K Ctrl+O (Windows/Linux) or Cmd+K Cmd+O (macOS) to open a folder in VS Code.

Managing Files and Folders:
1.Rename Files and Folders:
Right-click on a file or folder in the Explorer panel and select "Rename" to change its name.
Alternatively, use the keyboard shortcut F2 to rename the selected file or folder.
2.Delete Files and Folders:
Right-click on a file or folder and choose "Delete" to remove it from your workspace.
Be cautious as this action is permanent and cannot be undone directly from within VS Code.
3.Move and Copy Files:
Drag and drop files or folders within the Explorer panel to move them to a different directory.
Use the context menu options (e.g., "Copy", "Cut", "Paste") to copy, cut, and paste files or folders.

Navigating Between Files and Directories:
1.Using the Explorer Panel:
The Explorer panel in the Activity Bar provides a tree view of your workspace's file and folder structure. You can navigate by expanding/collapsing folders and clicking on files to open them.
2.Quick Open:
Use the keyboard shortcut Ctrl+P (Windows/Linux) or Cmd+P (macOS) to open the Quick Open dialog. You can then start typing the filename to quickly navigate to and open a specific file.
3.Switch Between Open Files:
Use the keyboard shortcut Ctrl+Tab (Windows/Linux) or Cmd+Tab (macOS) to switch between open files in the editor.
Alternatively, use Ctrl+1, Ctrl+2, etc., to switch to a specific numbered tab in the editor.
4.Go to File:
Use the keyboard shortcut Ctrl+P (Windows/Linux) or Cmd+P (macOS) followed by @ to navigate to a symbol or file in your workspace quickly.


10. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
Accessing Settings:
1.Open Settings:
Click on the gear icon (⚙️) in the Activity Bar on the sidebar, then select "Settings."
Alternatively, use the keyboard shortcut Ctrl+, (Windows/Linux) or Cmd+, (macOS) to open the Settings view directly.
2.Explore Settings Categories:
The Settings view is divided into several categories (e.g., Workbench, Editor, Extensions). Click on a category to view and modify its settings.
3.Search Settings:
Use the search bar in the Settings view to quickly find specific settings or preferences by typing keywords or phrases.

Customizing Settings:
1.Changing Theme:
Open Settings:
Access the Settings view using the methods mentioned above.
2.Search for Themes:
In the search bar, type "Color Theme" or "Theme" to find theme-related settings.
3.Select a Theme:
Under "Color Theme," click on the dropdown menu and choose a theme from the available options (e.g., Dark+, Light+, Solarized Light).
4.Save Changes:
VS Code will automatically apply the selected theme. Close the Settings view to save the changes.

Adjusting Font Size:
1.Open Settings:
Access the Settings view using the methods mentioned earlier.
2.Search for Font Size:
In the search bar, type "Font Size" to find font-related settings.
3.Set Font Size:
Adjust the "Editor: Font Size" slider to increase or decrease the font size according to your preference.
4.Save Changes:
Close the Settings view to save the changes. The font size in the editor will be updated accordingly.

Customizing Keybindings:
1.Open Keyboard Shortcuts:
Click on the gear icon (⚙️) in the Activity Bar on the sidebar, then select "Keyboard Shortcuts."
Alternatively, use the keyboard shortcut Ctrl+K Ctrl+S (Windows/Linux) or Cmd+K Cmd+S (macOS) to open Keyboard Shortcuts directly.
2.Search for Keybindings:
In the Keyboard Shortcuts view, use the search bar to find specific keybindings or commands.
3.Edit Keybindings:
Double-click on a keybinding to edit it. You can also add new keybindings or remove existing ones.
4.Save Changes:
Close the Keyboard Shortcuts view to save the changes to your custom keybindings.



11. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Setting up and starting debugging in Visual Studio Code (VS Code) involves configuring debug configurations and utilizing various debugging features. 
Steps to Set Up and Start Debugging:
1.Open Your Project:
Open the folder or workspace containing your program files in VS Code.
2.Create a Launch Configuration:
Click on the Debug icon in the Activity Bar on the sidebar (or use the keyboard shortcut Ctrl+Shift+D).
Click on the gear icon (⚙️) in the Debug view toolbar and select "Add Configuration."
Choose the appropriate environment for your program (e.g., Node.js, Python, C++, etc.) or create a custom configuration.
3.Configure Launch Settings:
Modify the launch settings in the generated launch.json file according to your program's requirements (e.g., specify the program entry point, arguments, environment variables, etc.).
4.Set Breakpoints:
Navigate to the file where you want to set breakpoints (lines where the debugger will pause execution).
Click in the gutter area next to the line numbers to set breakpoints. A red dot will appear indicating the breakpoint.
5.Start Debugging:
Click on the green play icon (▶️) in the Debug view toolbar to start debugging using the selected configuration.
Alternatively, use the keyboard shortcut F5 to start debugging.
6.Debugging Controls:
While debugging, use the debugging controls in the Debug view toolbar or keyboard shortcuts to control program execution (e.g., play/pause, step over, step into, step out, restart, stop).
7.Inspect Variables and Expressions:
Use the Variables view in the Debug sidebar to inspect the values of variables and expressions during debugging.
Hover over variables in the editor to see their current values.
8.Debug Console:
Access the Debug Console in the Debug sidebar to interactively run code and execute expressions during debugging sessions.

Key Debugging Features in VS Code:
1.Multi-Language Support:
VS Code supports debugging for various programming languages and environments, including JavaScript/Node.js, Python, C/C++, Java, etc.
2.Breakpoints:
Set breakpoints to pause program execution at specific lines of code for inspection and troubleshooting.
3.Watch and Variables View:
Monitor and inspect variables, expressions, and object properties in real-time using the Watch and Variables views during debugging.
4.Call Stack:
View and navigate the call stack to understand the sequence of function calls leading up to the current point of execution.
5.Debug Console:
Use the Debug Console to execute commands, evaluate expressions, and interactively debug code snippets during debugging sessions.
6.Debugging Controls:
Utilize debugging controls (play/pause, step over, step into, step out, restart, stop) to control program execution and navigate through code while debugging.
7.Integrated Terminal:
Access an integrated terminal within VS Code for running debugged programs or executing additional commands related to debugging.
     

11. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
   Integrating Git with Visual Studio Code (VS Code) for version control involves setting up a Git repository, making commits to track changes, and pushing those changes to a remote repository on platforms like GitHub. 
Initializing a Git Repository:
1.Open Your Project:
Open the folder or workspace of your project in VS Code.
2.Open the Source Control View:
Click on the Source Control icon in the Activity Bar on the sidebar (or use the keyboard shortcut Ctrl+Shift+G).
3.Initialize a Git Repository:
Click on the "Initialize Repository" button (if your project is not already a Git repository). This action creates a .git folder in your project directory, initializing Git version control.

Making Commits:
1.Stage Changes:
In the Source Control view, you'll see a list of modified files. Click on the "+" icon next to a file to stage it for commit. Alternatively, stage all changes by clicking on the "+" button above the file list.
2.Write Commit Message:
Enter a descriptive commit message in the text box provided below the file list. This message should briefly summarize the changes made in the commit.
3.Commit Changes:
Click on the checkmark icon (✓) to commit the staged changes. This action creates a new commit in your Git history.

Pushing Changes to GitHub:
1.Add Remote Repository (GitHub):
If you haven't already linked your local repository to a remote repository (e.g., GitHub), click on the ellipsis (...) in the Source Control view and select "Add Remote."
Enter the URL of your GitHub repository and a name for the remote (usually "origin").
2.Push Commits to GitHub:
After committing your changes locally, click on the ellipsis (...) again in the Source Control view and select "Push."
Choose the branch you want to push (usually "main" or "master"), and click "OK" to push your commits to the remote repository on GitHub.
Pull Changes: Before pushing changes to GitHub, it's a good practice to pull any changes from the remote repository to ensure your local branch is up to date. Use the "Pull" button in the Source Control view for this.
Branching and Merging: VS Code provides tools for creating new branches, switching between branches, and merging branches. Explore the branch-related options in the Source Control view for branching operations.
Visual Diff Viewer: VS Code's Source Control view includes a visual diff viewer that allows you to review changes before committing. Use this feature to review and stage specific changes selectively.

      

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

