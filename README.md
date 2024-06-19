[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15294224&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11


1.check System Requirements
   - Ensure your device meets Windows 11 specs.

 2.Backup Data
      - Save important files.

  3.Download Windows 11   - Visit [Windows 11 Download Page](https://www.microsoft.com/software-download/windows11).

     4.Select Installation Method:
         - Use Installation Assistant, create installation media, or download the ISO file.

 5 Install Windows 11
   - Follow on-screen instructions for your chosen method.

  6.Post-Installation - Configure settings and restore data.
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


1. Visit the Download Page:
   - Go to [Visual Studio Code Download](https://code.visualstudio.com/Download).

 2.Download the Installer:
   - Select the appropriate version for your operating system (Windows, macOS, Linux).

3.Run the Installer:
    - Open the downloaded file and follow the installation prompts.

4.Complete Installation
    - Accept the license agreement, choose installation location, and select additional tasks if desired.

5.Launch Visual Studio Code:
    - Open the application and start customizing your setup with extensions and settings.
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   1.Install Git
   - Download and install Git from [git-scm.com](https://git-scm.com/downloads).
   2.Configure Git:
   open your terminal or command prompt and run:
    ```sh
    git config --global user.name "https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Masingita25/tree/main"
   git config --global user.email "mwkhosa25@gmail.com"
   3. Create a GitHub Account:
    - Sign up at [GitHub](https://github.com).
   4. Initialize a Git Repository:
   - Navigate to your project directory and run:

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
1. Download Python
1. Visit the Python Official Website:
   Go to [www.python.org](https://www.python.org).
2. Navigate to the Downloads Section:
   - On the homepage, hover over the "Downloads" tab.
   - The website should automatically suggest the latest version suitable for your operating system (Windows, macOS, or Linux).
3. Download the Installer:
   - Click the suggested download link or choose a specific version from the list.
2. Install Python
1. Run the Installer:
   - Locate the downloaded installer file (usually in your Downloads folder).
   - Double-click the installer to run it.
2.Modify Installation Options:
   - On the first screen, check the box that says "Add Python to PATH." This is crucial for running Python from the command line.
   - Click "Install Now" for a standard installation or "Customize Installation" if you need specific options.
3.Complete the Installation:
   - The installer will take a few minutes to set up Python on your system.
   - Once complete, you’ll see a success message. Click "Close."
3.Verify Python Installation
1.Open a Command Line Interface (CLI):
   - On Windows: Open Command Prompt (search for `cmd` in the Start menu).
   - On macOS: Open Terminal.
   - On Linux: Open Terminal.
2. Check Python Version:
  Type the following command and press Enter:
   ```bash
   python --version
   ```
   or
   ```bash
   python3 --version
   ```
You should see the installed Python version number.
4. Install Necessary Packages and Tool
1.Install `pip`
   - `pip` is the package installer for Python. It should come bundled with Python 3.4 and later. Verify its installation by typing:
     ```bash
     pip --version
   ```
  - If `pip` is not installed, follow the instructions on the [pip installation page](https://pip.pypa.io/en/stable/installation/).
2.Install Project-Specific Packages:
   - Use `pip` to install the necessary packages for your project. For example, to install Flask and Requests, type:
     ```bash
     pip install flask requests
     ```
3.Set Up a Virtual Environment (Optional but Recommended):
   - A virtual environment helps manage dependencies for different projects.
   - Create a virtual environment by running:
     ```bash
     python -m venv myenv
     ```
   - Activate the virtual environment:
     - On Windows:
       ```bash
       myenv\Scripts\activate
      ```
     - On macOS/Linux:
       ```bash
       source myenv/bin/activate
      ```
5.Verify Your Setup
1. Create a Test Script:
   - Create a simple Python script to ensure everything is working. Open your favorite text editor and write:
     ```python
     print("Hello, Python!")
     ```
2.Run the Script:
   - Save the file as `test.py`.
   - In the command line, navigate to the directory where `test.py` is saved and run:
     ```bash
     python test.py
    ```
   - You should see the output: `Hello, Python!`
6. Additional Tools (Optional)
1. Install an Integrated Development Environment (IDE):
   - Popular choices include PyCharm, VS Code, and Jupyter Notebook.
2.Install Additional Interpreters or Runtimes if Needed:
   - For example, if your project requires Node.js, download and install it from [nodejs.org](https://nodejs.org).
3.Version Control:
   - Install Git from [git-scm.com](https://git-scm.com) to manage your project's source code
5. Install Package Managers:
   If applicable, install package managers like pip (Python).
1. Installing `pip` for Python
Step 1: Check if Python is installed
First, ensure that Python is installed on your system. Open a terminal (Command Prompt, PowerShell, or terminal on macOS/Linux) and type:
```sh
python --version
```
or
```sh
python3 --version
```
This should return the version of Python installed. If Python is not installed, you need to install it first. You can download it from the [official Python website](https://www.python.org/downloads/).
 Step 2: Download `get-pip.py`
 To install `pip`, you need to download the `get-pip.py` script. You can do this directly from the terminal using `curl` or `wget`:
 ```sh
 curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
 ```
 or
 ```sh
 wget https://bootstrap.pypa.io/get-pip.py
 ```
 Step 3: Run the `get-pip.py` script
 Once you have `get-pip.py`, you can run the script to install `pip`:

 ```sh
 python get-pip.py
 ```
 or
 ```sh
 python3 get-pip.py
 ```
 Step 4: Verify the installation
 After the installation completes, you can verify that `pip` is installed correctly by checking its version:
 ```sh
 pip --version
 ```
 or
 ```sh
 pip3 --version
 ```
 This should display the version of `pip` installed on your system.
  2. Installing `pip` on macOS using Homebrew
  If you're using macOS, you can also install `pip` via Homebrew, a package manager for macOS.
  Step 1: Install Homebrew
  If Homebrew is not already installed, you can install it by running the following command in the terminal:
  ```sh
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
  Step 2: Install Python (which includes `pip`)
  Use Homebrew to install Python:
  ```sh
  brew install python
  ```
  This command installs the latest version of Python and `pip`.
   3. Installing `pip` on Linux
   Many Linux distributions include `pip` in their package repositories.
   Step 1: Update package list
   First, update the package list to ensure you get the latest version available:
   ```sh
   sudo apt update
   ```
    Step 2: Install `pip`
    For Python 2:
    ```sh
    sudo apt install python-pip
    ```
    For Python 3:
    ```sh
    sudo apt install python3-pip
    ``` 
    Step 3: Verify the installation
    Check the version of `pip` to ensure it is installed correctly:
    ```sh
    pip --version
    ```
    or
    ```sh
    pip3 --version
    ```

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
1: Download MySQL Installer
1. Go to the [MySQL downloads page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. Under "MySQL Installer 5.7 for Windows," choose the appropriate version for your system. Typically, you would select the `mysql-installer-community` version.
3. Click on the "Download" button next to your chosen version.
Step 2: Initiate the Download
1. You will be redirected to the MySQL login page. You can either login if you have an Oracle account or click on "No thanks, just start my download" to proceed without logging in.
2. Save the file to your computer.
Step 3: Run the MySQL Installer
1. Once the download is complete, locate the installer file (usually in your Downloads folder) and double-click it to run the installer.
2. If prompted by User Account Control (UAC), click "Yes" to allow the installer to make changes to your device.
Step 4: Choose Setup Type
1. The MySQL Installer will start. On the first screen, choose the setup type that best fits your needs:
   - Developer Default: Installs the MySQL server and other development tools.
   - Server only: Installs only the MySQL server.
   - Client only: Installs only the MySQL client tools.
   - Full: Installs all MySQL products.
   - Custom: Allows you to choose which products and features to install.
2. For most users, "Developer Default" is a good choice. Select it and click "Next."
Step 5: Check Requirements
1. The installer will check for any missing requirements and offer to download them if necessary. Click "Execute" to download and install the missing prerequisites.
Step 6:Install MySQL Products
1. The installer will present a list of My
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Step 1: Set Up Your Local Development Environment
1. Install a Code Editor or IDE:
  - Popular options include Visual Studio Code, PyCharm, and IntelliJ IDEA.
    - Download and install the one that best suits your needs.
    2. Install Version Control System:
      - Install Git to manage your code versions and collaborate with others. 
        - Download Git from [git-scm.com](https://git-scm.com/) and follow the installation instructions.
        3. Install Programming Language Runtimes:
           - Install the runtime for the programming language you'll be using (e.g., Node.js for JavaScript, Python, Ruby).
             - Follow the official installation guide for your operating system.
             Step 2: Set Up Virtual Environments
             1. For Python:
                - Create a virtual environment:
                     ```bash
                          python -m venv myenv
                               ```
                                  - Activate the virtual environment:
                                       - On Windows:
                                              ```bash
                                                     myenv\Scripts\activate
                                                            ```
                                                                 - On macOS/Linux:
                                                                        ```bash
                                                                               source myenv/bin/activate
                                                                                      ```
                                                                                      2. For Node.js (using `nvm`):
                                                                                         - Install `nvm` (Node Version Manager):
                                                                                              ```bash
                                                                                                   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
                                                                                                        ```
                                                                                                           - Install and use a specific version of Node.js:
                                                                                                                ```bash
                                                                                                                     nvm install node
                                                                                                                          nvm use node
                                                                                                                               ```
                                                                                                                                Step 3: Set Up Docker for Containerization
                                                                                                                                1. Install Docker:
                                                                                                                                   - Download and install Docker from [docker.com](https://www.docker.com/products/docker-desktop).
                                                                                                                                      - Follow the installation instructions for your operating system.
                                                                                                                                      2. Create a `Dockerfile`:
                                                                                                                                         - Create a file named `Dockerfile` in your project directory.
                                                                                                                                           - Define the environment in the `Dockerfile`. Example for a Node.js application:
                                                                                                                                                ```dockerfile
                                                                                                                                                     # Use an official Node.js runtime as a parent image
                                                                                                                                                          FROM node:14
                                                                                                                                                               # Set the working directory in the container
                                                                                                                                                                    WORKDIR /usr/src/app
                                                                                                                                                                         # Copy the package.json and install dependencies
                                                                                                                                                                              COPY package*.json ./
                                                                                                                                                                                   RUN npm install
                                                                                                                                                                                        # Copy the rest of the application code
                                                                                                                                                                                             COPY . .
                                                                                                                                                                                                  # Expose port 8080
                                                                                                                                                                                                       EXPOSE 8080
                                                                                                                                                                                                            # Run the application
                                                                                                                                                                                                                 CMD ["node", "app.js"]
                                                                                                                                                                                                                      ```
                                                                                                                                                                                                                      3. Build the Docker Image:
                                                                                                                                                                                                                         - In your terminal, navigate to your project directory and run:
                                                                                                                                                                                                                              ```bash
                                                                                                                                                                                                                                   docker build -t my-app .
                                                                                                                                                                                                                                        ```
                                                                                                                                                                                                                                        4. Run the Docker Container:
                                                                                                                                                                                                                                           - Start the container:
                                                                                                                                                                                                                                                ```bash
                                                                                                                                                                                                                                                     docker run -p 8080:8080 my-app
                                                                                                                                                                                                                                                          ```
                                                                                                                                                                                                                                                          Step 4: Use Virtual Machines (Optional)
                                                                                                                                                                                                                                                          1. Install Virtual Machine Software:
                                                                                                                                                                                                                                                             - Install software like VirtualBox or VMware.
                                                                                                                                                                                                                                                                - Download VirtualBox from [virtualbox.org](https://www.virtualbox.org/) and follow the installation instructions.
                                                                                                                                                                                                                                                                2. Create a Virtual Machine:
                                                                                                                                                                                                                                                                   - Open VirtualBox and click "New" to create a new virtual machine.
                                                                                                                                                                                                                                                                      - Follow the prompts to configure the VM (name, type, memory size, etc.).
                                                                                                                                                                                                                                                                      3. Install the Operating System:
                                                                                                                                                                                                                                                                         - Download an ISO file of the operating system you want to use (e.g., Ubuntu).
                                                                                                                                                                                                                                                                            - Attach the ISO file to the VM and start it to begin the OS installation process.
                                                                                                                                                                                                                                                                            4. Set Up Development Environment in VM:
                                                                                                                                                                                                                                                                               - After the OS is installed, set up the development environment inside the VM as you would on a physical machine.
                                                                                                                                                                                                                                                                                Step 5: Ensure Consistency Across Environments
                                                                                                                                                                                                                                                                                1. Use `.env` Files for Environment Variables:
                                                                                                                                                                                                                                                                                   - Create a `.env` file to manage environment-specific configurations.
                                                                                                                                                                                                                                                                                      - Example `.env` file:
                                                                                                                                                                                                                                                                                           ```env
                                                                                                                                                                                                                                                                                                DATABASE_URL=your_database_url
                                                                                                                                                                                                                                                                                                     SECRET_KEY=your_secret_key
                                                                                                                                                                                                                                                                                                          ```
                                                                                                                                                                                                                                                                                                          2. Use Configuration Management Tools:
                                                                                                                                                                                                                                                                                                             - Tools like Ansible, Puppet, or Chef can help automate the setup of development environments.
                                                                                                                                                                                                                                                                                                             3. Document Setup Instructions:
                                                                                                                                                                                                                                                                                                                - Create a `README.md` file with detailed setup instructions for your project.
                                                                                                                                                                                                                                                                                                                   - Include steps to clone the repository, set up the environment, and run the project.
                                                                                                                                                                                                                                                                                                                   By following these steps, you can set up a robust and consistent development environment, leveraging the power of virtualization tools to ensure that your project runs smoothly across different machines
8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
1. Visual Studio Code (VS Code)
 Step 1: Open VS Code
 Launch Visual Studio Code.
 Step 2: Access Extensions View
 Click on the Extensions icon in the Activity Bar on the side of the window or press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS).
 Step 3: Search for Extensions
 In the Extensions view, type keywords related to the functionality you need (e.g., "Python", "ESLint", "Prettier").
  Step 4: Install an Extension
  1. Browse the search results.
  2. Click on an extension to view its details, including description, usage instructions, and reviews.
  3. Click the `Install` button to add the extension to VS Code.
   Step 5: Configure the Extension
   1. Some extensions may require additional configuration.
   2. Go to `File > Preferences > Settings` or press `Ctrl+,` (Windows/Linux) or `Cmd+,` (macOS).
   3. Use the search bar to find specific settings or navigate through the categories.
    2. Sublime Text
    Step 1: Open Sublime Text
    Launch Sublime Text.
     Step 2: Install Package Control
     1. Press `Ctrl+` (backtick) to open the console.
     2. Paste the following code and press Enter:
        ```python
        import urllib.request,os,hashlib; h = '9253c99045b1927fcb5e0e5ff5e66b60fba8e23d5c2c72d1af9a2f4c4bb9c6cb'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen('http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); if dh != h: raise Exception('Error validating download (got %s instead of %s), please try manual install' % (dh, h)); with open(os.path.join(ipp, pf), 'wb') as f: f.write(by)
        ```
     3. Restart Sublime Text.
     Step 3: Open Command Palette
     Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS).
      Step 4: Install Packages
      1. In the Command Palette, type `Package Control: Install Package` and press Enter.
      2. Type the name or keywords of the package you need and select it from the list.
       Step 5: Configure the Package
       1. Some packages may require additional configuration.
       2. Go to `Preferences > Package Settings` to find and configure installed packages.
        3. Atom
         Step 1: Open Atom
         Launch Atom.
          Step 2: Open Settings
          Click on `File > Settings` or press `Ctrl+,` (Windows/Linux) or `Cmd+,` (macOS).
          Step 3: Access Install Section
          Go to the `Install` tab on the left sidebar.
           Step 4: Search for Packages
           1. In the `Install` tab, type the name or keywords of the package you need.
           2. Click the `Install` button next to the desired package.
            Step 5: Configure the Package
            1. Go to `Settings > Packages` to manage and configure installed packages.
             4. PyCharm/IntelliJ IDEA
              Step 1: Open PyCharm/IntelliJ IDEA
              Launch your IDE.
               Step 2: Open Plugins Settings
               Go to `File > Settings > Plugins` (Windows/Linux) or `PyCharm > Preferences > Plugins` (macOS).
                Step 3: Browse Marketplace
                Click on `Marketplace` to browse available plugins.
                 Step 4: Search for Plugins
                 1. Type the name or keywords of the plugin you need.
                 2. Click the `Install` button next to the desired plugin.
                 Step 5: Configure the Plugin
                 1. Plugins can often be configured via `File > Settings > Plugins` or `Preferences > Plugins`.
                  Popular Extensions and Plugins to Consider
                   Visual Studio Code (VS Code)
                   - Python: For Python development.
                   - ESLint: Integrates ESLint into VS Code.
                   - Prettier - Code formatter: For automatic code formatting.
                   - GitLens: Enhances Git capabilities within VS Code.
                    Sublime Text
                    - Anaconda: Python IDE with autocompletion, linting, and more.
                    - SublimeLinter: Framework for linting code.
                    - Emmet: High-speed HTML and CSS workflow.
                     Atom
                     - ide-python: Python IDE capabilities.
                     - linter-eslint: Integrates ESLint into Atom.
                     - prettier-atom: Integrates Prettier for code formatting.
                     PyCharm/IntelliJ IDEA
                     - Python: Enhances Python support.
                     - Docker: Integrates Docker support.
                     - GitToolBox: Enhances Git capabilities.
                      Conclusion
                      By exploring and installing extensions or plugins, you can greatly enhance the functionality of your text editor or IDE, making your development environment more efficient and tailored to your specific needs. Be sure to read the documentation and reviews to ensure you are selecting the best tools for your workflow.
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
 1. Installing Visual Studio Code
 1. Download VS Code: Visit the [Visual Studio Code website](https://code.visualstudio.com/) and download the appropriate version for your operating system (Windows, macOS, or Linux).
 2. Install VS Code: Run the installer and follow the installation instructions.
  2. Installing Extensions
  1. Open Extensions View:
     - Launch VS Code.
     - Click on the Extensions icon in the Activity Bar on the side of the window or press `Ctrl+Shift+X`.
  2. Search and Install Extensions:
     - **ESLint**:
       - Search for "ESLint" in the Extensions view.
       - Click `Install` next to the ESLint extension.
     - Prettier:
       - Search for "Prettier - Code formatter".
       - Click `Install` next to the Prettier extension.
     - GitLens:
       - Search for "GitLens — Git supercharged".
       - Click `Install` next to the GitLens extension.
     - Debugger for Chrome:
       - Search for "Debugger for Chrome".
       - Click `Install`.
  3. Configuring Extensions
  1. ESLint Configuration:
     - Open the command palette (`Ctrl+Shift+P`) and type “ESLint: Create ESLint configuration”.
     - Follow the prompts to set up the configuration file (`.eslintrc.json`).
     - Add the following to `settings.json` to enable auto-fixing:
       ```json
       "eslint.autoFixOnSave": true
       ```
  2.Prettier Configuration:
     - Create a Prettier configuration file (`.prettierrc`) in the project root:
       ```json
       {
         "singleQuote": true,
         "trailingComma": "es5"
       }
       ```
     - Add the following to `settings.json` to use Prettier as the default formatter:
       ```json
       "editor.formatOnSave": true,
       "editor.defaultFormatter": "esbenp.prettier-vscode"
       ```
  3. GitLens Configuration:
     - GitLens usually works out of the box, but you can customize it through `settings.json` if needed. For example:
       ```json
       "gitlens.advanced.messages": {
         "suppressShowKeyBindingsNotice": true
       }
       ```
  4.Debugger for Chrome Configuration:
     - Create a `launch.json` file in the `.vscode` folder to configure the debugger:
       ```json
       {
         "version": "0.2.0",
         "configurations": [
           {
             "type": "chrome",
             "request": "launch",
             "name": "Launch Chrome against localhost",
             "url": "http://localhost:3000",
             "webRoot": "${workspaceFolder}"
           }
         ]
       }
       ```
   4. Customizing the Environment
   1. Themes:
      - Install themes from the Extensions view (e.g., “One Dark Pro”).
      - Set the theme in `settings.json`:
        ```json
        "workbench.colorTheme": "One Dark Pro"
        ```
   2. Font and Editor Settings:
      - Customize font settings in `settings.json`:
        ```json
        "editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace",
        "editor.fontSize": 14,
        "editor.fontLigatures": true
        ```
   3. File Icons:
      - Install a file icon theme (e.g., “Material Icon Theme”).
      - Set the icon theme in `settings.json`:
        ```json
        "workbench.iconTheme": "material-icon-theme"
        ```
    5. Troubleshooting
    1. Extension Not Working:
       - Ensure the extension is enabled.
       - Check for any conflicting extensions.
       - Restart VS Code after installing or updating extensions.
    2. Linting Issues:
       - Verify the ESLint configuration file (`.eslintrc.json`) is correct.
       - Ensure ESLint is installed locally in the project (`npm install eslint --save-dev`).
    3. Formatting Issues:
       - Ensure Prettier is set as the default formatter.
       - Check the Prettier configuration file (`.prettierrc`) for any syntax errors.
    4. GitLens Not Displaying Information:
       - Check that the repository is initialized and there are commits.
       - Verify Git is installed and accessible from the command line.
    6. Conclusion
    This document provides a comprehensive guide to setting up and customizing a developer environment in Visual Studio Code
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
