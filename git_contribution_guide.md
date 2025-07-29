# How to Contribute to a Friend's Git Repository

This guide outlines the standard workflow for contributing to a project on a platform like GitHub, GitLab, or Bitbucket.

### The Workflow: Fork, Clone, Branch, Push, Pull Request

This is the most common and recommended workflow. It ensures you can work on your own copy without affecting the original project until you're ready.

**Step 1: Fork the Repository**

First, you need your own server-side copy of your friend's repository.

1.  Go to your friend's repository page on GitHub (or a similar site).
2.  In the top-right corner, click the **"Fork"** button.
3.  This will create a complete copy of the project under your own account.

**Step 2: Clone Your Fork to Your Local Machine**

Now, you need to get the code onto your computer to work on it.

1.  Go to the page for **your fork** (not the original one).
2.  Click the green **"< > Code"** button.
3.  Copy the URL provided (HTTPS is usually easiest).
4.  Open your terminal and run the `git clone` command:
    ```bash
    git clone <paste_the_url_you_just_copied>
    ```
5.  This will download the repository into a new folder on your computer. Navigate into it:
    ```bash
    cd <repository_name>
    ```

**Step 3: Create a New Branch for Your Changes**

It's a best practice to make your changes on a separate branch. This keeps your work organized and separate from the main codebase.

*   Give your branch a descriptive name, like `feature/add-cool-button` or `fix/login-error`.
    ```bash
    git checkout -b <your-branch-name>
    ```

**Step 4: Make Your Changes**

This is where you do the actual work!

*   Add new files, edit existing ones, and fix bugs using your favorite code editor.

**Step 5: Commit Your Changes**

Once you're happy with your changes, you need to save them to the branch's history.

1.  **Stage** your changes. This tells Git which files you want to include in the next commit. To add all modified files, use:
    ```bash
    git add .
    ```
2.  **Commit** the staged files with a clear, descriptive message about what you did.
    ```bash
    git commit -m "feat: Add a new button to the main page"
    ```

**Step 6: Push Your Branch to Your Fork**

Now, you need to upload your new branch and its commits to your fork on GitHub.

*   The first time you push a new branch, you need to tell Git where to send it:
    ```bash
    git push --set-upstream origin <your-branch-name>
    ```
*   For any subsequent pushes on the same branch, you can just use:
    ```bash
    git push
    ```

**Step 7: Open a Pull Request (PR)**

This is the final step where you ask your friend to review your work and merge it into their original project.

1.  Go to the page for **your fork** on GitHub.
2.  You should see a banner that says **"Compare & pull request"**. Click it.
3.  If you don't see it, go to the "Pull requests" tab and click "New pull request".
4.  Make sure the base repository is your friend's project and the head repository is your fork and your branch.
5.  Write a clear title and description for your pull request, explaining what you changed and why.
6.  Click **"Create pull request"**.

Your friend will then be notified. They can review your code, leave comments, and (if they're happy with it) merge your contribution into their project.
