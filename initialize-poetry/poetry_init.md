	# Setting Up API Development Environment 
	
	**Note:** I am a Linux user and cannot run these commands on my system. If you encounter any errors, try solving them by browsing the internet. If you still do not understand how to resolve the error, feel free to contact me.
	
	This guide covers the installation of `pipx` and `poetry` and initializing a project with `poetry` using the Command Prompt.
	
	## Step 1: Install pipx
	
	1. Open Command Prompt as an Administrator.
	2. Run the following command to install `pipx` using Python:
	
	   ```cmd
	   python -m pip install --user pipx
	   python -m pipx ensurepath
	   ```
	
	3. Restart your Command Prompt to ensure the `pipx` command is available.
	4. Verify the installation:
	
	   ```cmd
	   pipx --version
	   ```
	
	## Step 2: Install Poetry Using pipx
	
	1. Use `pipx` to install `poetry` globally:
	
	   ```cmd
	   pipx install poetry
	   ```
	
	2. Verify the installation:
	
	   ```cmd
	   poetry --version
	   ```
	
	## Step 3: Initialize a Project Using Poetry
	
	1. Navigate to the directory where you want to create your project:
	
	   ```cmd
	   cd path\to\your\directory
	   ```
	
	2. Create a new folder for your project:
	
	   ```cmd
	   mkdir my_project
	   cd my_project
	   ```
	
	3. Initialize the project with `poetry`:
	
	   ```cmd
	   poetry init
	   ```
	
	   Follow the prompts to configure your project.
	
	4. Install dependencies (if any):
	
	   ```cmd
	   poetry add <dependency_name>
	   ```
	
	5. To activate the virtual environment for your project:
	
	   ```cmd
	   poetry shell
	   ```
	
	6. To run your project:
	
	   ```cmd
	   python main.py
	   ```
	
	---
	
	Your API development environment is now set up and ready to use!
