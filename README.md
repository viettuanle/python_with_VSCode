How to use Visual Studio Code to write python code

1. Install Visual Studio Code
2. Install Python: Download Python from the official website: https://www.python.org/downloads/, add Python PATH variable to your system environment by check the box "Add Python to PATH" during installation.
3. Create a new folder for your project, and open it in Visual Studio Code.
4. Create a new file with a .py extension, abd write your python code in the file.
5. Save the file, and execute the script.
6. For practical, let create new virtual environment for your project, and install the required packages. To do this, let : Open the terminal in Visual Studio Code by pressing `` Ctrl + `  ``
   or View > Terminal , then run the following commands:
   `python -m venv myvenv`
   `./myvenv/Scripts/activate  ## activate it.`
   `pip install library_name_here`
7. If you use git, let do this:
   deactivate ## after this, will come back to your project, not inside virtual environment.
   git init ## initialize a new git repository.
   git add . ## add all files to the staging area.
   git commit -m "Initial commit" ## commit the changes.
   git remote add origin https://github.com/your_username/your_repository.git ## add the remote repository.
   git push -u origin master ## push the changes to the remote repository.
