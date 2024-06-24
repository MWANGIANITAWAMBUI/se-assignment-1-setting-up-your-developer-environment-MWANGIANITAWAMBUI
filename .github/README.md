[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15322856&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

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
Setting Up Your Developer Environment

Download Windows 11 from the Microsoft Windows 11 download page.

Create a bootable USB drive using the Windows Media Creation Tool.

Restart your computer and boot from the USB drive.

Follow on-screen instructions to install Windows 11.

Complete initial setup by configuring region, keyboard layout, and Microsoft account.

Download Visual Studio Code from the official website.

Run the installer and follow installation prompts.

Launch Visual Studio Code and configure basic settings like theme and font size.

Download Git from the official website.

Install Git and open Git Bash.

Configure Git with your user name and email:

bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub account at GitHub.

Create a new repository on GitHub.

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/your-repository.git
Initialize a Git repository and make your first commit:

bash
Copy code
cd your-repository
echo "# Your Project" > README.md
git add README.md
git commit -m "Initial commit"
git push origin main
Download Python from the official website.

Run the installer and check the option to "Add Python to PATH".

Verify installation:

bash
Copy code
python --version
Verify pip installation (pip is installed with Python by default):

bash
Copy code
pip --version
Update pip to the latest version:

bash
Copy code
python -m pip install --upgrade pip
Download MySQL Installer for Windows from here.

Run the installer and choose the "Developer Default" setup.

Configure MySQL server and create a root password.

Complete the installation and verify MySQL is running.

Download and install Docker Desktop from here (optional).

Follow installation prompts and start Docker Desktop.

Verify installation:

bash
Copy code
docker --version
Open Visual Studio Code and go to Extensions view (Ctrl+Shift+X).

Search for and install the following extensions:

Python
GitLens
Prettier - Code formatter
ESLint
Challenges and Solutions
Challenge: Git not recognized in the command prompt.

Solution: Added Git to system PATH manually by modifying environment variables.
Challenge: MySQL service failed to start after installation.

Solution: Re-ran the configuration wizard and ensured correct network settings were used.
Reflection
Setting up the developer environment was a comprehensive process involving multiple installations and configurations. Main challenges included ensuring all tools were correctly configured and troubleshooting issues like Git integration and MySQL service startup. Persistence and careful following of instructions were key to overcoming these challenges.
