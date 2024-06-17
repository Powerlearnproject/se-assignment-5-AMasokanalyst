[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15266735&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   
   #### PRE-REQUISITES
   When considering to install VS code, you must first know wish opering system you are using, like windows, mac os or linux. In this demonstration of installation we will be focusing on windows, windows 11 to be specific. Then you must make sure that you have administrative privileges to install an application in your computer in this case Visual Studio code, administrative privileges simply means that you have the necessary rights to install applications and make changes that affect all users on the computer. And lastly you must make sure that you have access to the internet for connection so that you can be able to download installation files.

   ### Steps to Download and Install Visual Studio Code

   1. **Visit the Visual Studio Code Website**:
   - Open your web browser and go to the official [Visual Studio Code website](https://code.visualstudio.com/).

   2. **Download the Installer**:
   - On the homepage, you will see a "Download for Windows" button. Click on it.
   - This will download the VS Code setup file (typically named `VSCodeSetup-x64-<version>.exe`).

   3. **Run the Installer**:
   - Navigate to your Downloads folder or the location where the setup file was saved.
   - Double-click on the `VSCodeSetup-x64-<version>.exe` file to run the installer.

   4. **Start the Installation Process**:
   - A User Account Control (UAC) prompt might appear asking for permission to make changes to your device. Click "Yes" to proceed.

   5. **Accept the License Agreement**:
   - In the setup window, read through the license agreement. Check the box to accept the terms and click "Next".

   6. **Select the Destination Location**:
   - Choose the installation location or leave it at the default path. Click "Next".

   7. **Select Additional Tasks**:
   - You will be given options to:
     - Create a desktop icon.
     - Add "Open with Code" actions to the Windows Explorer context menu (recommended).
     - Register Code as an editor for supported file types (recommended).
     - Add to PATH (recommended).
   - Select the options you prefer and click "Next".

   8. **Install Visual Studio Code**:
   - Click "Install" to start the installation process.
   - Wait for the installer to complete the installation. This may take a few minutes.

   9. **Launch Visual Studio Code**:
   - Once the installation is complete, you will see a completion window.
   - Check the box to launch Visual Studio Code and click "Finish".


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   
   **Configurations**

   Initial configurations and settings you must consider to adjust immediately after installation I think it should be the theme and appearance, so that you can choose a working environment that will be easy on your eyes, because some screen color are know to cause some irritation or discomfort to the eyes. to set up this configuration you must:
   Launch VS code > Click File > Click Preferences > Click Theme > Click Color Theme, then choose what you prefer.

   Another important configuration you might want to consider adjusting is AutoSave, to save yourself from having to constantly save manually any changes you making on you files. To set up AutoSave you must:
   Launch VS code > Click File > Click AutoSave
   
   **Extension**

   Extension that you must consider installing for optimal coding environment, include Live server: which is very helpful when designing a webpage using HTML, CSS and JavaScript; code formatting extension like prettier which automatically format your code on save; language extensions like python which allow you to create or edit python files on Visual Studio code. To install these extension you can simply Click the extension icon on the far left window of your Visual Studio. or by just clicking Ctrl + Shift + X on your keyboard on Windows. or you can also Click View > Click Extension. When the extension Window pops-up Search for the extension you wish to install, select it and Click on install, it will install.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Visual Studio code have a well-organized, easy to follow user interface. Its components are are layed out in a way that they will help enhance development workflow. 
   main components of VS code user interface include:
      
      **Activity Bar:** Is located vertically on the far left window of VS code with atleast five icons, each icon is designed to perform certain activity such as: Explorer, Search, Source Control, Run and Debug and Extensions. This window provides us with quick access to different views and functions. 
      
      **Side Bar:** A vertical pane located on the right of the activity bar, this bar displays a content associated with the icon selected on the activity bar.
      
      **Editor Group:** Central area where you can open and edit your files, it allows us to open as many files as we can. It can also be split in sections.
      
      **Status Bar:** located horizontal at the bottom of the window, its function is to provide us with the information of the current state of the workspace. Displaying indicators such as: current git branch, current problems, current ports forwarded, go-to line/column, indentation, encoding, end-of-line sequence, language mode.  

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   
   **Command Palette**

   With VS Code, the Command Palette is a crucial tool for boosting productivity since it enables you to complete a wide range of activities quickly and effectively. You can access command palette using keyboard shortcut "Ctrl + Shift + P" or you can access it by "click View > click Command Palette". There are many activities you can perfom using command palette, the most common ones include: opening files, changing language, installing extensions, git commands, formating code, searching settings, the list goes on and on.



5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   
   **Role of Extensions in VS code**

   A vital component of Visual Studio Code (VS Code) are extensions, which enhance productivity and allow for customization to meet unique development requirements by bringing additional features and capabilities to the editor. Aside from debuggers, linters, themes, and other tools, extensions can support a variety of programming languages.

   **Finding Extensions:** Extensions can be found via keyboard shortcut "Ctrl + Shift + X" or by clicking the fifth icon on the activity bar or by command palette.
   
   **Installing Extensions:** Extensions are very easy to install, after you have found extension through the aforementioned methods, extension pane will appear on the side bar, you can just type the name of the extension you want to install, then you will select it and hit "install"

   **Managing Extensions:** To manage extensions, you can just view the extensions, then you will see the installed extensions listed on the side bar, then you can select the extension you want to manage, it will then be displayed on the editor bar. then you can either disable or enable, uninstall or even update the extension.

   **Some Essential Extensions To Install include:**
   
   Prettier:
   prettier ensures uniform code formatting for many languages and projects.

   ESlint:
   ESlint helps to preserve the quality of the code by locating and resolving troublesome JavaScript and TypeScript patterns.

   Live Server:
   live server gives instant feedback by automatically reloading the page when a file is changed.

   Path intellisense:
   Makes it simpler to navigate and refer to files by autocompleting file paths in your workspace.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   
  **Integrated Terminal:** is one of the most useful features of Visual Studio Code, which allows you perform command-line tasks right inside the editor. By integrating terminal chores and code editing into one interface, this offers a smooth development experience. You can access integrated terminal by looking for it on View in the navigation menu or via command palette or by keyboard shortcut "Ctrl + ` ".

  **Advantages of Integrated Terminal**
  Using integrated terminal is advantageous because it offers Convenience: by making it unnecessary to switch between various applications; The integrated terminal opens automatically in the root directory of the project, starting inside the context of your current workspace. Compared to an external terminal, this requires less setup and navigation. Integrated terminal also offer synchronization: by making sure that when transferring between projects, file system modifications are reflected and the terminal is opened properly (in the correct directory).


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   With features like Explorer view, Command Palette, Quick Open, and keyboard shortcuts, VS Code provides sophisticated way to create, manage files and folders and even navigate between files and folders.

   **Creating a file or folder:** You can use the navigation menu : "click File > New File" then write the write the name of your file followed by the extension of the programming language you want to create, for example .py for python file or .html for html file. You can also open the Explorer view, right-click on the desired directory, select New File, enter the file name, and press Enter. To create a new folder, open the Explorer view, right-click on the desired directory, select New Folder, enter the folder name, and press Enter.

   **Opening a folder or a file:** To open a file in the editor, navigate to the file in the Explorer View, use the Command Palette, or open a folder using the menu or Command Palette. Navigate to the desired file and press Enter.

   **managing folders and files:** To rename files and folders, use the Explorer View, right-click, select Rename, enter new name, press Enter. Move files and folders using Drag and Drop or Cut and Paste.

   **Efficient navigation:** To switch between files in an editor, use Quick Open, Open Editors View, Breadcrumb Navigation, File Explorer, Shortcuts, Switching Tabs, and Navigate to Previous or Next Editors. Quick Open allows you to select a file name, Open Editors View lists open files, and Breadcrumb Navigation allows quick navigation between directories. File Explorer allows you to collapse and expand folders.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   To change the theme and font size in Visual Studio Code (VS Code), follow these steps:

      1. Open the Settings UI by searching for "Theme" in the settings search bar.
      2. Select a theme from the dropdown menu under "Color Theme" and press Enter.
      3. Open the Command Palette by pressing Ctrl + Shift + P.
      4. Type "Preferences: Color Theme" and press Enter.
      5. Change the font size by searching for it in the settings search bar and changing the value in the Editor: Font Size setting.
      6. Change keybindings by opening the Keyboard Shortcuts editor by pressing Ctrl + K, Ctrl + S.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Visual Studio Code (VS Code) is a powerful tool for debugging code efficiently. To set up and start debugging, follow these steps:

      1. Install necessary extensions, such as Python, by pressing Ctrl + Shift + X.
      2. Open your project and open the main file where you want to start debugging.
      3. Add a Debug Configuration by clicking on the Debug icon in the Activity Bar or pressing Ctrl + Shift + D.
      4. Set breakpoints in your code by clicking in the gutter to the left of the line numbers in the editor.
      5. Start debugging by selecting the configuration you created from the dropdown menu and pressing F5 to start debugging.

   Key debugging features in VS Code include breakpoints, step over, step into, step out, variable inspection, watch expressions, call stack, Debug Console, conditional breakpoints, logpoints, and exception handling.
   Starting debugging by pressing F5 will pause the execution at the breakpoint, allowing you to inspect variables and step through the code.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Visual Studio Code (VS Code) is a powerful tool for version control, allowing users to integrate Git with their projects. To integrate Git with VS Code, follow these steps:

      1. Install Git on your system: Download and install it from git-scm.com, Homebrew, or your package manager.
      2. Initialize a Git repository: Open your project in VS Code and navigate to your project directory. Open the Source Control View and click the button to create a new Git repository.
      3. Make changes and commit: Stage changes by clicking the + icon next to each file or in the Changes section header. Write a commit message and commit the changes.
      4. Connect to GitHub: Create a new repository on GitHub and add the remote repository as a remote in VS Code.
      5. Push changes to GitHub: Push your changes to the remote repository using the git push command.

    Key features for Git integration in VS Code include the Source Control View, viewing diffs, branching, and the GitLens extension for enhanced Git integration. Access Git commands through the Command Palette, such as Git: Clone, Git: Fetch, and Git: Pull.

    **Source**
      https://chatgpt.com/


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

