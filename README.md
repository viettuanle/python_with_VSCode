## How to use Visual Studio Code to write python code

1. Install Visual Studio Code
2. Install Python: Download Python from the official website: https://www.python.org/downloads/, add Python PATH variable to your system environment by check the box _Add Python to PATH_"\* during installation, otherwise set Python path manually.
3. Create a new folder for your project, and open it in Visual Studio Code.
4. Create a new file with a .py extension, abd write your python code in the file.
5. Save the file, and execute the script.
6. For practical, let create new virtual environment for your project, and install the required packages. To do this, let : Open the terminal in Visual Studio Code by pressing ** Ctrl + ` **
   or **View > Terminal** , then run the following commands:
   ```
   python -m venv myvenv
   ./myvenv/Scripts/activate  ## activate it.
   pip install library_name_here
   ```
7. If you use git, let deactivate to make suare come back to the project directory (not environemnt directory):
   ```
   ./myvenv/Scripts/deactivate
   ```
   Then run the following commands:
   ```
   git init ## initialize a new git repository.
   git add . ## add all files to the staging area.
   git commit -m "Initial commit" ## commit the changes.
   git remote add origin https://github.com/your_username/your_repository.git ## add the remote repository.
   git push -u origin master ## push the changes to the remote repository.
   ```
8. Should create file name _README.md_, md stand for markdown. (Markdown is a lightweight markup language with plain text formatting syntax. It is widely used for formatting readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.) You can write in markdown format such as:

```
# for heading 1,  ## for heading 2, ### for heading 3, etc.
* for bullet point, ** for bold, _ for italic, ` for inline code,
/`/`/` for code block, /`/`/`
Links are created with Square brackets for the text,followed by parentheses for the URL.
[OpenAI](https://www.openai.com)
Images are similar to links but with an exclamation mark ! at the beginning.
![Alt text](https://example.com/image.jpg)
Blockquotes are created using the > symbol.
> This is a blockquote.


```
