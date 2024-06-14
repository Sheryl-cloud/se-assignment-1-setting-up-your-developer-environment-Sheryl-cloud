[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15273665&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   Certainly! Here's a step-by-step guide on how to install Windows 11:

The first step is to Make sure your computer meets the system requirements for Windows 11 and Back up any important data on your computer to prevent data loss during the installation process.

Step 1: Create Installation Media
1. Visit the official Microsoft website to download the Windows 11 installation media creation tool.
2. Run the tool and follow the on-screen instructions to create a bootable USB drive or DVD with the Windows 11 installation files.

Step 2: Access BIOS/UEFI Settings
1. Insert the bootable USB drive or DVD into your computer.
2. Restart your computer and enter the BIOS or UEFI settings.Consult your computer's manual for the exact key.
3. In the BIOS/UEFI settings, set the boot order to prioritize booting from the USB drive or DVD.

Step 3: Begin Windows 11 Installation
1. Save the changes in BIOS/UEFI settings and restart your computer.
2. Your computer will boot from the USB drive or DVD, and you'll see the Windows 11 installation screen.
3. Select your language, time, and keyboard preferences, then click "Next."
4. Click "Install now" to begin the installation process.

Step 4: Enter Product Key (If Required)
1. If prompted, enter your Windows 11 product key. You can usually find this on the packaging or in the email if you purchased Windows 11 digitally.
2. Click "Next" to continue.

Step 5: Accept License Terms
1. Read and accept the license terms by checking the box, then click "Next."

Step 6: Choose Installation Type
1. Select the type of installation you want. Choose "Custom: Install Windows only (advanced)" for a clean installation.
2. Select the partition where you want to install Windows 11, then click "Next."

Step 7: Wait for Installation
1. Windows 11 will now be installed on your computer. This process may take some time, so be patient.
2. Your computer may restart several times during the installation process. Do not interrupt the process.

Step 8: Set Up Windows 11
1. Once the installation is complete, you'll be prompted to set up Windows 11.
2. Follow the on-screen instructions to personalize your settings, including creating user accounts, choosing privacy options, and connecting to a network.

Step 9: Install Drivers and Updates
1. After Windows 11 is installed, it's a good idea to install any necessary drivers for your hardware.
2. Visit the manufacturer's website for your computer or individual components to download and install the latest drivers.
3. Install any available Windows updates to ensure your system is up to date.

Step 10: Enjoy Windows 11
1. Once all drivers and updates are installed, you're ready to enjoy Windows 11!
2. Explore the new features and improvements, and customize your system to your liking.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Step 1: Download Visual Studio Code
1. Open your web browser and navigate to the official Visual Studio Code website: [Visual Studio Code](https://code.visualstudio.com/).
2. Once on the website, you'll see a prominent "Download for Windows" button. Click on it to start downloading the installer.

Step 2: Run the Installer
1. Once the download is complete, locate the downloaded installer file. It's usually located in your Downloads folder.
2. Double-click on the installer file (typically named something like "VSCodeSetup.exe") to run it.

Step 3: Install Visual Studio Code
1. The installer will launch and display the Visual Studio Code Setup Wizard. Click "Next" to continue.
2. Read and accept the license agreement, then click "Next."
3. Choose the destination folder where you want to install Visual Studio Code, or leave the default location, and click "Next."
4. Select additional tasks if desired (e.g., creating desktop shortcuts), then click "Next."
5. Finally, click "Install" to begin the installation process.

Step 4: Complete Installation
1. The installer will now install Visual Studio Code on your computer. This may take a few moments.
2. Once the installation is complete, click "Finish" to exit the Setup Wizard.

Step 5: Launch Visual Studio Code
1. After installation, you can launch Visual Studio Code by double-clicking its icon on the desktop or by searching for "Visual Studio Code" in the Start menu.
2. Visual Studio Code will open, and you're ready to start coding!

Step 6: Optional - Install Extension
1. Visual Studio Code supports a wide range of extensions that enhance its functionality for various programming languages and workflows.
2. To install extensions, click on the Extensions view icon in the Activity Bar on the side of the window (or press Ctrl+Shift+X).
3. Search for the extensions you want to install, then click the "Install" button next to each extension.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Step 1: Install Git
1. Visit the official Git website: [Git - Downloads](https://git-scm.com/downloads).
2. Download the appropriate installer for your operating system (Windows, macOS, Linux).
3. Run the installer and follow the on-screen instructions to complete the installation. Make sure to choose the default options unless you have specific preferences.

Step 2: Configure Git
1. Open a terminal or command prompt.
2. Set your name with the following command, replacing "Your Name" with your actual name:
   ```
   git config --global user.name "Your Name"
   ```
3. Set your email address with the following command, replacing "your.email@example.com" with your actual email address:
   ```
   git config --global user.email "your.email@example.com"
   ```

Step 3: Create a GitHub Account
1. Visit the GitHub website: [GitHub](https://github.com).
2. Click on the "Sign Up" button and follow the prompts to create a new GitHub account. You'll need to provide a username, email address, and password.

Step 4: Initialize a Git Repository
1. Open a terminal or command prompt.
2. Navigate to the directory where you want to create your project. Use the `cd` command to change directories.
3. Initialize a new Git repository by running the following command:
   ```
   git init
   ```
4. This command will create a hidden `.git` directory in your project folder, which Git uses to store information about the repository.

Step 5: Make Your First Commit
1. Create some files in your project directory or add existing files to the directory.
2. Add the files to the staging area with the following command:
   ```
   git add .
   ```
   This command adds all files in the current directory to the staging area. If you only want to add specific files, replace `.` with the file names.
3. Commit the changes to the repository with a descriptive message using the following command:
   ```
   git commit -m "Initial commit"
   ```
   Replace `"Initial commit"` with your own commit message describing the changes you made.
4. Congratulations! You've made your first commit to your Git repository.

Step 6: Connect to GitHub
1. Go to [GitHub](https://github.com) and log in to your account.
2. Click on the "+" icon in the top right corner and select "New repository."
3. Follow the prompts to create a new repository on GitHub. You can choose a name, description, and other settings for your repository.
4. After creating the repository, you'll see instructions for pushing your existing repository from the command line. Follow these instructions to connect your local repository to the remote repository on GitHub.


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Step 1: Download Python
1. Open your web browser and navigate to the official Python website: [Python.org](https://www.python.org/).
2. On the homepage, you'll see a prominent button to download the latest version of Python. Click on it to proceed.

Step 2: Choose Python Version
1. Python releases two versions: Python 2 and Python 3. Python 2 is legacy and not recommended for new projects. Choose the latest version of Python 3.x for your project.
2. Click on the download button for the desired version to proceed.

Step 3: Run the Installer
1. Once the download is complete, locate the downloaded installer file.
2. Double-click on the installer file to run it.

Step 4: Customize Python Installation (Optional)
1. The installer will launch the Python Setup Wizard. You can customize the installation options if needed.
2. Make sure to check the box that says "Add Python to PATH" before proceeding. This will allow you to run Python from the command line.
3. Click "Install Now" to proceed with the default installation settings.

Step 5: Verify Python Installation
1. After the installation is complete, open a command prompt or terminal window.
2. Type the following command and press Enter:
   ```
   python --version
   ```
   This command will display the installed Python version. If you see the version number, Python is successfully installed.



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Step 1: Open Command Prompt or Terminal
   - Open Command Prompt on Windows or Terminal on macOS/Linux.

Step 2: Upgrade pip
   - Run the following command:
     ```
     python -m pip install --upgrade pip
     ```
   This command will upgrade `pip` to the latest version available.

Step 3: Verify Installation
   - To verify that `pip` has been successfully installed and upgraded, you can run:
     ```
     pip --version
     ```
   This command will display the version of `pip` installed on your system.

Step 4: (Optional) Install Additional Package Managers
   - Depending on your project's requirements, you might need to install additional package managers. For example, if you're working with JavaScript, you might need to install npm (Node Package Manager). Similarly, if you're working with Ruby, you might need to install RubyGems.
   - Follow the installation instructions provided on the respective websites for npm, RubyGems, or any other package manager you need.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Step 1: Download MySQL Installer
1. Open your web browser and navigate to the MySQL Community Downloads page: [MySQL Community Downloads](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. Scroll down to find the "MySQL Installer for Windows" section.
3. Click on the "Download" button for the MySQL Installer appropriate for your system (32-bit or 64-bit).

Step 2: Run the MySQL Installer
1. Once the installer is downloaded, locate the downloaded file (typically named something like "mysql-installer-community-version.exe").
2. Double-click on the installer file to run it.
3. If prompted by User Account Control, click "Yes" to allow the installer to make changes to your system.

Step 3: Choose Setup Type
1. In the MySQL Installer welcome screen, click "OK" to proceed.
2. On the Setup Type screen, choose "Developer Default" or "Server only" depending on your requirements. For most development purposes, "Developer Default" is sufficient.
3. Click "Next" to continue.

Step 4: Select Products to Install
1. On the Product Selection screen, you'll see a list of MySQL products available for installation.
2. Make sure "MySQL Server" is selected, as it's required for database functionality.
3. Optionally, you can select other products like MySQL Workbench for managing databases through a graphical interface.
4. Click "Next" to continue.

Step 5: Configure MySQL Server
1. On the MySQL Server Configuration screen, you can configure the MySQL Server settings.
2. Choose "Standalone MySQL Server / Classic MySQL Replication" for a basic standalone server setup.
3. Click "Next" to continue.

Step 6: Install MySQL Server
1. On the Installation screen, review the installation summary and click "Execute" to begin the installation process.
2. The installer will download and install the selected MySQL products. This may take some time depending on your internet connection speed.

Step 7: Complete the Installation
1. Once the installation is complete, you'll see a screen confirming the successful installation.
2. Click "Next" to proceed.
3. Optionally, you can choose to start MySQL Workbench or MySQL Shell immediately after installation.
4. Click "Finish" to exit the installer.

Step 8: Verify MySQL Installation
1. Open MySQL Workbench if you installed it, or open a command prompt.
2. Run the command to verify that the MySQL server is running
   You'll be prompted to enter the root password that you set during installation.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Exp/lore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Exploring extensions, plugins, and add-ons for your text editor or IDE can greatly enhance your coding experience and productivity. Here's how one can explore and install extensions for some popular text editors and IDEs:

Visual Studio Code:
1. Open Visual Studio Code.
2. Click on the "Extensions" view icon in the Activity Bar on the side of the window (or press Ctrl+Shift+X).
3. In the Extensions view, you can browse featured extensions, search for specific extensions, or explore popular categories like "Linters," "Themes," "Debuggers," etc.
4. Click on an extension to view more details, including a description, rating, and installation options.
5. To install an extension, click the "Install" button next to it.
6. Once installed, you may need to reload Visual Studio Code to activate the extension.

Sublime Text:
1. Open Sublime Text.
2. Go to the "Preferences" menu and select "Package Control."
3. In the Package Control window, you can browse available packages by selecting "Install Package" or "List Packages."
4. You can also search for specific packages by selecting "Install Package" and typing the name of the package.
5. Once you find the package you want, select it to install it.

Atom:
1. Open Atom.
2. Go to the "File" menu and select "Settings" (on Windows/Linux) or "Atom" menu and select "Preferences" (on macOS).
3. In the Settings/Preferences view, click on the "Install" tab.
4. You can browse available packages by typing in the search bar or by scrolling through the list.
5. Click on the "Install" button next to the package you want to install.

PyCharm:
1. Open PyCharm.
2. Go to the "File" menu and select "Settings" (on Windows/Linux) or "PyCharm" menu and select "Preferences" (on macOS).
3. In the Settings/Preferences view, select "Plugins" from the left sidebar.
4. Click on the "Marketplace" tab to browse available plugins.
5. You can search for specific plugins by typing in the search bar or by scrolling through the list.
6. Click on the "Install" button next to the plugin you want to install.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    Sure, here's a comprehensive document outlining the steps taken to set up a developer environment, including configurations, customizations, and troubleshooting steps:



Developer Environment Setup Guide

 Table of Contents
1. Introduction
2. Operating System Setup
3. Text Editor/IDE Installation
4. Version Control System Setup
5. Programming Language Setup
6. Database Setup
7. Package Managers Installation
8. Extensions and Plugins Exploration
9. Summary



 1. Introduction
This guide provides step-by-step instructions for setting up a developer environment on a Windows system. The environment includes essential tools for software development, such as a text editor/IDE, version control system, programming language runtime, database management system, package managers, and extensions/plugins.


 2. Operating System Setup
- Installed Windows 11 operating system following the official installation guide.

 3. Text Editor/IDE Installation
- Installed Visual Studio Code from the official website.
- Explored available extensions for syntax highlighting, linting, code formatting, and version control integration.

4. Version Control System Setup
- Installed Git and configured it with name and email using command line.
- Created a GitHub account for hosting repositories.
- Initialized a Git repository for the project and made the first commit.


 5. Programming Language Setup
- Installed Python from Python.org.
- Ensured pip (Python package manager) was installed and upgraded to the latest version.
- Explored additional package managers like npm and RubyGems, depending on project requirements.


 6. Database Setup
- Downloaded and installed MySQL database from dev.mysql.com.
- Configured MySQL server with default settings.
- Verified installation and connectivity using MySQL Workbench.
 7. Package Managers Installation
- Verified the installation of pip for Python package management.
- Explored additional package managers like npm for JavaScript projects.

 8. Extensions and Plugins Exploration
- Explored available extensions/plugins/add-ons for Visual Studio Code, Sublime Text, Atom, and PyCharm.
- Installed extensions/plugins/add-ons for syntax highlighting, linting, code formatting, and version control integration based on project requirements.



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
