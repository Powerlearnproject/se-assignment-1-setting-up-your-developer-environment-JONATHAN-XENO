[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281571&assignment_repo_type=AssignmentRepo)
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

Operating System Installation: Install the preferred operating system (e.g., Windows, macOS, Linux).

Development Tools Installation: Install essential software like Visual Studio Code, Git, and a programming language runtime (e.g., Node.js, Python).

Version Control Setup: Configure Git with global settings (name, email) and connect to a remote repository (e.g., GitHub).

Environment Configuration: Set up environment variables, paths, and dependencies necessary for development (e.g., npm, pip).

IDE and Extensions: Customize Visual Studio Code with relevant extensions for your programming needs (e.g., ESLint, Python).

Testing and Deployment Tools: Install additional tools for testing (e.g., Jest, Selenium) and deployment (e.g., Docker, AWS CLI).

Documentation and Collaboration: Set up tools for documentation (e.g., Markdown editors) and collaboration (e.g., Slack, Microsoft Teams).

Security and Backup: Implement security measures (e.g., antivirus, firewall) and set up backup solutions for project files and data.

Continuous Integration/Continuous Deployment (CI/CD): Set up CI/CD pipelines using tools like Jenkins, GitHub Actions, or Azure DevOps.

Final Checks: Validate installations, configurations, and integrations to ensure the environment is ready for software development.

For detailed instructions, consult specific software documentation and platform guidelines to ensure accurate setup and configuration of each tool and service.

Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

ANSWER

Operating System Installation
  Installed Windows 11 on my primary development machine.
Development Tools Installation
  Installed Visual Studio Code as my primary Integrated Development Environment (IDE).
  Installed Git for version control and linked it to my GitHub account.

Environment Configuration
  Configured Git with global settings (git config --global user.name "Your Name" and git config --global user.email "jonathantrevor9@gmail.com").
 Added Git credentials to the Windows Credential Manager for seamless authentication.

IDE and Extensions
  Customized Visual Studio Code settings for tab size, theme (Dark+), and font (Fira Code).
  Installed VS Code extensions: python, prettier, django, flutter, dart.

Security and Backup
  Installed antivirus software (Windows Defender) and configured firewall settings.
  Enabled automatic backup of important project files to a cloud storage service (Google Drive).

Troubleshooting Encountered
  Git SSH Key Setup: Encountered issues with SSH key setup for GitHub; resolved by generating a new SSH key pair and 
adding it to GitHub.

Final Checks
  Verified Git operations (clone, pull, push) with a sample repository.
  Tested VS Code extensions functionality (linting, formatting) in different projects.


Reflecting on the challenges faced during the setup of my developer environment, several key obstacles emerged, along with strategies employed to overcome them:

Git SSH Key Setup: Initially encountered difficulties setting up SSH keys for GitHub authentication. My solution involved generating a new SSH key pair and carefully following GitHub's documentation to add the public key to my GitHub account.

Visual Studio Code Extensions: Some extensions didn't work as expected or conflicted with each other. Mitigated by carefully selecting and testing extensions before integrating them into my workflow. I regularly updated extensions to leverage new features and fixes.

IDE Customization: Customizing Visual Studio Code (VS Code) settings and extensions initially led to performance issues and conflicts. Iresolved this by selectively enabling extensions based on project needs, optimizing settings for performance, and periodically reviewing and pruning unused extensions.

I also faced a difficulty in initializing a new repository locally and syncing it with GitHub due to errors in remote repository URL setup or permissions. I solved this by double-checking remote repository URLs and ensuring proper authentication credentials were configured locally (git remote add origin <repository-url>). Used Git commands (git init, git add ., git commit -m "Initial commit", git push -u origin main) step-by-step to initialize and push changes to GitHub, ensuring repository setup was correct.
