# Day Two Recipe
Step-by-step recipe for creating a new working project environment

1. Create repository

- Go to Github and create a new repository, giving it a name and optional description.

2. Create & open a new Codespace

- Code --> Codespace --> "+"
- Click the 3 dots to the right of your Codespace name, and select "Open in Visual Studio Code"
- This will automatically take you to VS Code, with your Codespace up and running.

3. Create a .py file to contain your code

- File --> New File
- Name your file, including .py at the end of it
- Make your .py file interactive by adding section breaks: #%%

4. Set up a virtual environment

- Open a new terminal
- Type: python3 -m venv .venv
- Type: source .venv/bin/activate
- This creates and activates your virtual environment, which you can do all of your project-specific work in.

5. Requirements.txt file

- Check to see if a requirements.txt file already exists by typing "ls" in the terminal.
- If it does, load the dependencies to your environment by typing: pip install -r requirements.txt
- If it does not, type "pip freeze > requirements.txt" to generate the file from your environment which contains all required packages, then install.

6. Push changes to GitHub

- In the terminal, type: git status
- Type: git add .
- Type: git commit -m "Add project files and update requirements"
- Type: git push origin main
- This will update your GitHub repository with all changes made.
