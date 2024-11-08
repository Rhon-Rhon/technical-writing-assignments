# How to submit technical writing assignments to GitHub/Gitee

This topic will guide you through the process of submitting your technical writing assignments to GitHub or Gitee.

## 1. Choose a platform

- GitHub: Internationally popular code hosting platform
- Gitee: Popular code hosting platform in China

Both platforms have similar operations, so use the one specified by your instructor.

## 2. Create an account

If you don't already have an account, register on the specified platform.

## 3. Install Git

1. Visit <https://git-scm.com/downloads>
2. Download and install the appropriate Git version for your operating system
3. After installation, open the command line (CMD or PowerShell on Windows, Terminal on Mac or Linux)
4. Verify the installation by entering:

    ```bash
    git –version
    ```

    If it displays the Git version number, the installation was successful.

## 4. Configure Git

Enter the following commands in the command line to set your username and email:

```bash
git config –global user.name “Your Name”git config –global user.email “your.email@example.com”
```

## 5. Clone the assignments repository

1. Open the command line
2. Navigate to the directory where you want to store the project, for example:

    ```bash
    cd Documents/Projects
    ```

3. Use the following command to clone the repository:

    ```bash
    git clone https://github.com/amber-moe/technical-writing-assignments.git
    ```

## 6. Add your assignment files

1. Copy your assignment files to the appropriate location in the cloned repository directory
2. You can do this using the file manager or command line, for example:

cp ~/Documents/my-assignment.md .

## 7. Commit and push your changes

1. Check the file status:

    ```bash
    git status
    ```

    This will show which files have been modified or added

2. Add your files to the staging area:

    ```bash
    git add .
    ```

    This will add all new and modified files

3. Commit your changes:

    ```bash
    git commit -m “Add technical writing assignment: [topic]”
    ```

    Replace [topic] with your assignment topic

4. Push your changes to the remote repository:

    ```bash
    git push origin main
    ```

    Note: The branch name (main) may be different. Confirm with your instructor

## 8. Organize your assignments

- Place your files in the correct directories as specified by your instructor
- Use clear file names, e.g., "assignment1_user_manual.md"
- Update the README.md file if required

## 9. Verify submission

1. Check the repository on GitHub/Gitee website to ensure your files have been uploaded successfully
2. View your commit history on the "Commits" page
3. Inform your instructor that you've submitted your assignment, providing any necessary details

## 10. Updates and revisions

If you need to update your assignment:

1. Make changes to your local files
2. Check the status:

    ```bash
    git status
    ```

3. Add the changed files:

    ```bash
    git add .
    ```

4. Commit the changes:

    ```bash
    git commit -m “Update technical writing assignment: [specific update]”
    ```

5. Push the updates:

    ```bash
    git push origin main
    ```

## Common issues and solutions

- If you encounter an error when pushing, you may need to pull the latest changes first:

    ```bash
    git pull origin main
    ```

Then try pushing again

- If you encounter merge conflicts, seek help from your instructor to resolve them

Remember to follow any specific instructions provided by your instructor regarding file formats, naming conventions, or submission procedures. Don't hesitate to ask your instructor for help if you have any questions.
