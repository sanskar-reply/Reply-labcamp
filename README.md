# Reply Labcamp

This project utilizes a Python 3 virtual environment to manage dependencies effectively and isolate it from other projects on your system. Let's walk through the steps to set up the environment and execute the code:

## Setting Up the Environment

### 1. Creating the Virtual Environment**
Open your terminal or command prompt.

Navigate to the root directory of your project.

Execute the following command to create a virtual environment named venv:

```bash
python3 -m venv venv
```
### 2. Activating the Virtual Environment
Linux/macOS:

```bash
source venv/bin/activate
```
Windows:

```bash
venv\Scripts\activate
```  
### 3. Verification
Once activated, your terminal prompt will typically prefix with the virtual environment name (e.g., (venv)). This indicates that you're operating within the isolated environment.

### 4. Using the Virtual Environment in VS Code
Launch Visual Studio Code and open your project.
In the bottom-left corner, you should see the current Python environment being used. Click on it.
Select the venv environment you just created. This ensures VS Code uses the correct interpreter and packages for your project.

### 5. Running Code
With the virtual environment active in your terminal and selected in VS Code, you can now run the shared jupyter notebooks.
