# in-class-ls-exercise


# Linux Home Directory Contents Assignment

## Overview

Welcome to the Linux Home Directory Contents Assignment! The goal of this assignment is to help you practice using basic Linux commands and working with Git. Specifically, you will demonstrate your ability to list the contents of your home directory, save this information to a file, and then commit and push that file to your GitHub repository.

## Objective

- Use the `ls` command to capture the contents of your home directory.
- Redirect the output of the `ls` command into a text file.
- Commit the file containing the directory listing to your GitHub repository.
- Push the committed file to your GitHub repository.
- Your submission will be automatically graded using GitHub Actions.

## Instructions

### Step 1: Set Up Your Repository

1. Accept the assignment on GitHub Classroom, which will create a repository for you.
2. Clone your repository to your local machine using the following command (use the ssh version of the repository url):

   ```bash
   git clone <your-repository-url>
   ```

### Step 2: List Home Directory Contents

1. In your terminal, use the `ls` command to list the contents of your home directory.
2. Redirect the output of the `ls` command to a file named `home_directory.txt` by running the following command:

   ```bash
   ls ~ > home_directory.txt
   ```

   This command will create a file named `home_directory.txt` in your current directory with the contents of your home directory.

### Step 3: Commit Your Work

1. Stage the `home_directory.txt` file for commit using:

   ```bash
   git add .
   ```

2. Commit the changes with a meaningful message:

   ```bash
   git commit -m "Added home directory contents"
   ```

3. Push your changes to GitHub:

   ```bash
   git push
   ```

### Step 4: Verify Submission

After pushing your changes, GitHub Actions will automatically run a test to check if your `home_directory.txt` file contains the correct output. The test will pass if the content of your file exactly matches the output of the `ls ~` command.

## Evaluation

Your assignment will be evaluated automatically using GitHub Actions based on the following criteria:

- The file `home_directory.txt` is present in your repository.
- The contents of `home_directory.txt` match the output of the `ls ~` command on your system.

## Tips for Success

- Use the `cat` command to check the contents of `home_directory.txt` before committing.
- Make sure the file name is spelled correctly (`home_directory.txt`).
- Ensure that the file contains the complete and correct output of the `ls ~` command.

## Submission

Once you have completed the above steps, your work will be automatically submitted when you push the changes to your GitHub repository. Make sure to check the results of the GitHub Actions workflow to confirm that your submission is correct.

Good luck, and have fun learning Linux!
