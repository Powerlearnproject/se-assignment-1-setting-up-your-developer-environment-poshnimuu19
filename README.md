[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15256528&assignment_repo_type=AssignmentRepo)
# Dev_Setup
# Assignment: Setting Up My Developer Environment

## Objective
This assignment aims to familiarize me with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give me the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

## Tasks

### 1. Select My Operating System (OS)
#### I Choose an operating system that best suits my preferences and project requirements.

#### Download and Install Windows 11
1. Go to the [Windows 11 download (https://www.microsoft.com/software-download/windows11).
2.I Followed the instructions to download the Windows 11 installation media.
3. Use the installation media to install Windows 11 on my machine.


### 2. Install a Text Editor or Integrated Development Environment (IDE)
#### Select and install a text editor or IDE suitable for my programming languages and workflow.

#### Download and Install Visual Studio Code
1. Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
2. I Selected the appropriate version for my OS and downloaded the installer which is Windows as seen the image below.

3. Run the installer and follow the setup wizard to install Visual Studio Code.


### 3. Set Up Version Control System
#### Install Git and configure it on my local machine.
1. Download Git from the [Git website](https://git-scm.com/downloads).

2. Run the installer and follow the setup wizard to install Git.
3. Open a terminal or command prompt and configure Git with my username and email:
   ```sh
   git config --global user.name "My Name"
   git config --global user.email "my.email@example.com"
   ```

#### Create a GitHub account for hosting my repositories.
1. Go to [GitHub](https://github.com) and sign up.

#### Initialize a Git repository for my project and make my first commit.
1. Open a terminal or command prompt.
2. Navigate to my project directory.
3. Initialize a new Git repository:
   ```sh
   git init
   ```
4. Add my files to the repository:
   ```sh
   git add .
   ```
5. Commit the changes:
   ```sh
   git commit -m "Initial commit"
   ```
6. Push the changes to GitHub:
   ```sh
   git remote add origin https://github.com/myusername/my-repository.git
   git push -u origin master
   ```

### 4. Install Necessary Programming Languages and Runtimes
#### Install Python
1. Go to the [Python download page](http://www.python.org).
2. Download the latest version of Python for my OS.

3. Run the installer and ensure I check the box to add Python to my PATH during installation.

### 5. Install Package Managers
#### Install pip (Python's package manager)
1. Pip is installed by default with Python. Verify its installation by running:
   ```sh
   pip --version
   ```

### 6. Configure a Database (MySQL)
#### Download and install MySQL database
1. Visit the [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. Download the MySQL Installer for Windows.

3. Run the installer and follow the setup wizard to install MySQL.

### 7. Set Up Development Environments and Virtualization (Optional)
#### Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
1. Download and install Docker from the [Docker website](https://www.docker.com/get-started).
2. Following  the installation instructions.
3. Verify the installation by running:
   ```sh
   docker --version
   ```

### 8. Explore Extensions and Plugins
#### Explore available extensions, plugins, and add-ons for my chosen text editor or IDE, in mycase the visual studio code to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.

3. Search for and install the following recommended extensions via the provided search bar on the extension bar:
   - Python
   - GitLens
   - Docker
   - Prettier - Code formatter
   - ESLint

## Troubleshooting Steps
- **Git Configuration**: Ensure Git is added to the system PATH during installation.
- **Python Path Issue**: If Python is not recognized, add it to the system environment variables.
- **MySQL Installation**: If MySQL server does not start, check the error logs in the MySQL data directory.
```


