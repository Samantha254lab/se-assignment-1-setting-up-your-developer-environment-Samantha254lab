[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15272505&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
1. Create Installation Media:

Download the Windows 11 Installation Assistant as mentioned earlier.
Choose "Create installation media for another PC" and click "Next."
Select your preferred language, edition (Windows 11 Home or Pro), and architecture (64-bit).
Choose to create a bootable USB flash drive (minimum 8GB - existing data will be erased) or an ISO file (to create a bootable DVD).
Follow the on-screen instructions to complete the media creation.
2. Boot from the Installation Media:

Insert the bootable USB drive or DVD into your target PC and restart.
You might need to enter BIOS settings to change the boot order and prioritize the USB/DVD drive.
3. Begin the Clean Installation:

Follow the on-screen instructions during the Windows 11 setup process.
Choose your language, keyboard layout, and edition of Windows 11.
Select "Custom install" when prompted for the installation type.
During the drive selection stage, format the drive where you want to install Windows 11 (This will erase all data on that drive).
Follow the remaining on-screen instructions to complete the installation.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
    Download the Installer:

Head over to the official VS Code download page: [Download Visual Studio Code].

Select your operating system (Windows,).

Windows: Download the ".exe" installer for your system (32-bit or 64-bit based on your PC).
2. Run the Installer
 Double-click the downloaded ".exe" file.
In the installation wizard, you can choose the installation location (default is recommended) and select additional options like creating a desktop shortcut. Click "Install" to begin.

3. Launch VS Code:

Windows: You can find VS Code in your Start menu or by clicking the desktop shortcut (if created during installation).


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
1. Install Git:

Windows: Download the latest Git for Windows installer from https://www.git-scm.com/downloads. Run the installer and follow the on-screen instructions. Choose the option to use Git from the command line and consider setting up your desired text editor
2. Verify Installation:

Open a terminal window and type git --version. If Git is installed correctly, it will display the installed version number.
3. Configure Git (Optional):

Run the following commands in your terminal to configure your username and email address for Git commits:
Bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
Use code with caution.
content_copy
Replace "Your Name" and "youremail@example.com" with your actual information.
Creating a GitHub Account
Head over to https://github.com/ and sign up for a free GitHub account.
Initializing a Git Repository and Making a Commit
Create a Project Directory: Create a new directory on your local machine to store your project files.
Open Terminal in Project Directory: Open a terminal window and navigate to your project directory using the cd command. For example, if your project directory is named my-project, use cd my-project.
Initialize Git Repository: Run the command git init in your terminal. This creates a hidden .git folder in your project directory, initializing an empty Git repository.
Create a File: Create a new file within your project directory (e.g., index.html for a web page). Add some content to the file.
Add Files to Staging Area: Use the command git add . to add all files in your current directory to the staging area. The staging area tells Git which files you want to include in your next commit.
Commit Changes: Run the command git commit -m "Initial commit". This creates a snapshot of the files in the staging area and stores it in the Git repository history. The message in quotes is a brief description of your commit.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
1. Download the Installer:

Head over to the official Python download page: Download Python.
Select the latest stable version of Python 3 (recommended for new projects).
Download the appropriate installer for your operating system (Windows, macOS, or Linux).
2. Run the Installer:

Windows: Double-click the downloaded ".exe" file and follow the on-screen instructions. Make sure to check the option to "Add Python to PATH" during installation. This allows you to run Python commands from any directory in your terminal.

3. Verify Installation:

Open a terminal window and type python3 --version. If Python is installed correctly, it will display the installed version number.
Additional Considerations:

Virtual Environments (Recommended): For managing project dependencies and isolating project environments, consider using virtual environments. Tools like venv or virtualenv can help you create isolated environments for your projects.
Package Manager (pip): Python uses pip to install and manage additional libraries and packages. You can verify pip installation by running pip3 --version in your terminal. If not installed, refer to the official documentation for installation instructions: Install pip.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Verifying pip Installation (Recommended):

First, let's check if pip is already installed by opening a terminal window and typing:

Bash
pip3 --version
Use code with caution.
content_copy
If you see a version number displayed, then pip is already installed and ready to use.
Installing pip (if not found):

If pip is not found, the installation method depends on your operating system:

Windows:

Using Python Installer: During the official Python installer process for Windows, there's usually an option to "Add Python to PATH". If you checked this option, pip should be installed alongside Python.
Manual Installation (if not added to PATH): You can download get-pip.py from https://bootstrap.pypa.io/pip/2.7/get-pip.py and run it from your command prompt:
Bash
python get-pip.py
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Head over to the official MySQL downloads page: Download MySQL Community Server.
Choose the appropriate download based on your operating system (Windows, macOS, or Linux).
Windows: Download the installer (.msi or .zip) for your system architecture (32-bit or 64-bit).

Installation Process:

Windows:

Double-click the downloaded installer (.msi).
Follow the on-screen instructions during the MySQL Setup Wizard. It will guide you through configuration options like setting the root password, choosing the installation type (typical, custom, etc.), and selecting components to install.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Setting Up Development Environments with Virtualization (Optional)
Virtualization tools like Docker and Virtual Machines (VMs) can significantly improve your development workflow by:

Isolating project dependencies: Each project can have its own isolated environment, preventing conflicts between different projects or your main system.
Ensuring consistency: You can create a development environment with specific configurations and libraries, guaranteeing identical setups across different machines.
Here's a breakdown of these two popular options:

Virtual Machines (VMs):

Concept: VMs create a simulated computer system on your existing hardware. You can install a complete operating system like Windows, macOS, or Linux inside a VM, allowing you to run applications specific to that OS within your main system.
Benefits:
Isolation: Projects run in separate VMs, preventing dependency conflicts.
Consistency: Create VMs with predefined configurations for consistent environments.
Flexibility: Install different operating systems and software within VMs for diverse project needs.
Drawbacks:
Resource-intensive: VMs require a significant portion of your system resources (CPU, memory, storage).
Setup Time: Setting up and configuring VMs, especially complex environments, can be time-consuming.
Docker:

Concept: Docker uses containerization technology to package applications with their dependencies into lightweight, portable units called containers. These containers share the underlying operating system of your host machine but run in isolation.
Benefits:
Lightweight: Docker containers are much smaller and resource-efficient compared to VMs.
Faster Startup: Starting and stopping Docker containers is significantly faster than VMs.
Portability: Docker containers can be easily shared and run on any system with Docker installed.
Reproducibility: Dockerfiles define the container's configuration, ensuring consistent environments across machines.
Drawbacks:
Limited OS Choice: Docker containers typically inherit the host machine's operating system.
Learning Curve: Understanding Docker concepts and commands requires some initial learning.
Choosing the Right Tool:

Opt for VMs: If you need complete operating system isolation and the ability to run full-fledged applications from different operating systems.
Choose Docker: If you prioritize lightweight development environments, portability, faster startup times, and consistent configurations across machines.
Additional Resources:

Virtual Machines:
VirtualBox: Download VirtualBox
VMware Workstation Player: VMware Workstation Player [invalid URL removed]
Docker:
Docker Desktop: Download Docker Desktop
Docker Documentation: Docker Get Started

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   Syntax Highlighting:

Most modern text editors and IDEs come with built-in syntax highlighting for various programming languages. However, extensions can offer more extensive support and customization options.
Popular choices include:
Visual Studio Code: One Dark Pro, Solarized Dark, Material Theme
Sublime Text: Soda Dark, AOceanic Dark, Monokai
Linting:

Linting tools help identify potential errors and stylistic issues in your code. Extensions integrate these tools directly into your editor, providing real-time feedback.
Some examples:
Visual Studio Code: ESLint, JSHint, Pylint
Sublime Text: SublimeLinter, ESLint, Codacy
Code Formatting:

Code formatting ensures consistent indentation, spacing, and style across your codebase, improving readability and maintainability. Extensions provide automatic formatting based on defined styles.
Popular options include:
Visual Studio Code: Prettier, Beautify, EditorConfig
Sublime Text: Align Tab, Bracket Highlighter, Emmet
Version Control Integration:

Version control systems like Git track changes to your code over time. Extensions streamline interaction with Git, allowing you to commit, push, pull changes directly from your editor.
Some popular choices:
Visual Studio Code: GitLens, GitHub Pull Requests, Sourcetree
Sublime Text: GitGutter, Package Control Git, Sublime Merge

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
