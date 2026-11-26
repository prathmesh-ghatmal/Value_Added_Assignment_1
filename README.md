# Value Added Assignment 1 — HTML & CSS

## Important Instructions

- Complete all three tasks using **HTML and CSS only**.
- **AI tools are strictly prohibited.** Do not use ChatGPT, GitHub Copilot, Gemini, or any other AI tool to generate, write, modify, debug, or complete your assignment code.
- You must write the code entirely on your own and be able to explain every part of your implementation.
- Add meaningful comments in your code explaining the logic and approach you have used. Comments must reflect your actual understanding and must not be vague, irrelevant, or added merely to fulfil the requirement.
- **Read this entire README carefully before starting.** You are responsible for understanding and following all instructions provided here.
- You must follow the exact **Fork → Clone → Work → Commit → Push → Pull Request** workflow explained in this README. Do not skip steps or use a different submission method.
- Follow the exact folder structure and naming conventions specified in this README. Do not rename folders or place your files in incorrect locations.
- Make meaningful changes, complete your work properly, and commit your changes with meaningful commit messages that accurately describe the work done.
- Do not push your work directly to the original repository. Push your work to your own fork and submit a Pull Request.
- Submissions that do not follow the required structure, naming convention, Git workflow, or instructions may not be evaluated.


**Failure to follow the instructions mentioned in this README may result in your submission being rejected or not considered for evaluation.**

---

## Step 1: Open the Original Assignment Repository

Visit the original assignment repository using the link below:


**Original Repository:**  
https://github.com/prathmesh-ghatmal/Value_Added_Assignment_1


This repository contains all three tasks and the required reference images.

You must create your own fork of this repository before starting your assignment. Do not make changes directly to the original repository.

---

## Step 2: Fork the Repository

Forking creates your own copy of the original repository under your GitHub account.

1. Open the original repository link provided in Step 1.
2. Locate the **Fork** button near the top-right side of the repository page.
3. Click the **Fork** button.
4. GitHub will open the **Create a new fork** page.
5. Under **Owner**, select your own GitHub account.
6. Keep the **Repository name exactly the same as the original repository name**. Do not rename it.
7. Keep **Copy the main branch only** selected.
8. Click **Create fork**.
9. Wait for GitHub to create your fork.
10. Once created, verify that the repository is present under your GitHub username and that it is marked as forked from the original repository.

**Important:** You must use the fork created through this process. Do not create a new empty repository manually.

---

## Step 3: Clone Your Own Fork to Your Computer

After creating your fork, you must clone that fork to your local computer.

1. Open your fork under your own GitHub username.
2. Click the green **Code** button.
3. Make sure the HTTPS option is selected.
4. Copy the repository URL.
5. Open Terminal, Command Prompt, or the terminal inside VS Code.
6. Navigate to the directory where you want to keep your assignment.
7. Execute the following command, replacing `YOUR-USERNAME` with your GitHub username:

```bash
git clone https://github.com/YOUR-USERNAME/Value_Added_Assignment_1.git
```

For example, if your GitHub username is `student123`, the command would use your own repository URL.

8. After cloning completes, navigate into the repository:

```bash
cd Value_Added_Assignment_1
```

**Verify that you have cloned your own fork and not the original repository.**

---

## Step 4: Create Your Personal Submission Folder

Inside the cloned repository, locate the folder named:

```text
Students Submission
```

Inside this folder, you must create a folder using the following exact naming convention:

```text
FULL_ROLL_NUMBER_FIRSTNAME_LASTNAME
```

### Example

If your roll number is `2401055` and your name is Prathmesh Ghatmal, your folder name should be:

```text
2401055_Prathmesh_Ghatmal
```

### Naming rules

- Use your complete roll number.
- Use your first name followed by your last name.
- Use underscores (`_`) to separate the roll number, first name, and last name.
- Do not use spaces.
- Do not use nicknames, initials, or incomplete names.
- Do not create or modify another student's submission folder.
- Your work must be placed inside your own folder only.

Incorrect folder names or incorrect submission locations may result in your work not being evaluated.

---

## Step 5: Create the Required Folder Structure

Inside your personal submission folder, create three folders named exactly:

- `Task 1`
- `Task 2`
- `Task 3`

Each task folder must contain the following two files:

- `index.html` — HTML structure
- `style.css` — CSS styling

Your folder structure must look like this:

```text
Value_Added_Assignment_1/
│
└── Students Submission/
    │
    └── FULL_ROLL_NUMBER_FIRSTNAME_LASTNAME/
        │
        ├── Task 1/
        │   ├── index.html
        │   └── style.css
        │
        ├── Task 2/
        │   ├── index.html
        │   └── style.css
        │
        └── Task 3/
            ├── index.html
            └── style.css
```

Replace `FULL_ROLL_NUMBER_FIRSTNAME_LASTNAME` with your own correctly formatted folder name.


Do not change the names of the required folders or files.


---

## Step 6: Complete All Three Tasks

The repository contains reference images for Task 1, Task 2, and Task 3.


You must:

1. Open the reference image provided for Task 1.
2. Recreate the design using HTML and CSS.
3. Write your HTML structure in `Task 1/index.html`.
4. Write your CSS styling in `Task 1/style.css`.
5. Repeat the same process for Task 2 and Task 3 using their respective folders.
6. Link the CSS file correctly to the HTML file in each task.
7. Make sure each task can be opened and viewed in a browser.

Your objective is to recreate the given UI as accurately as possible, including layout, spacing, alignment, sizing, colours, typography, and other visible details.

Use only HTML and CSS for this assignment.

Do not use JavaScript, frameworks, CSS libraries, downloaded templates, or prebuilt UI code.

---

## Step 7: Code Quality and Comments

Your code must be written by you and must reflect your own understanding.

### Mandatory requirements

- Write the HTML and CSS yourself.
- Maintain proper indentation and readable code.
- Use appropriate HTML elements.
- Use CSS properties properly to achieve the required layout.
- Add meaningful comments explaining the approach or logic used in important parts of your code.
- Comments should explain **why or how you implemented a section**, not simply repeat the element or property name.
- Avoid unnecessary, meaningless, or repetitive comments.
- You must be able to explain your complete code during evaluation.
- You may be asked to modify your code or recreate a part of the UI during evaluation.

### Strictly prohibited

- AI-generated code.
- Copying code from other students.
- Copy-pasting complete solutions from the internet.
- Using prebuilt templates or ready-made UI implementations.
- Using JavaScript or any framework/library to complete the tasks.

If you cannot explain your submitted code or are unable to make modifications to it yourself, your submission may be considered invalid.

---

## Step 8: Review Your Work Before Committing

Before committing your changes, verify the following:

- All three tasks are completed.
- Each task has its own `index.html` and `style.css`.
- All files are inside your own submission folder.
- Your folder name follows the required naming convention.
- The HTML and CSS files are linked correctly.
- Your code is properly formatted and readable.
- You have added meaningful comments explaining your implementation.
- You have not included unrelated files or modified other students' submissions.
- You have personally checked your work in the browser.


You can check your modified files using:

```bash
git status
```

---

## Step 9: Commit Your Changes Using Meaningful Commit Messages

You must commit your work using Git.

First, check the changes:

```bash
git status
```

Stage your assignment files:

```bash
git add .
```

Commit your changes using a meaningful commit message:

```bash
git commit -m "Complete HTML CSS assignment tasks"
```

### Commit message rules

Commit messages must clearly describe the work performed.

**Examples of meaningful commit messages:**

```text
Completed Task 1 homepage layout
Implemented Task 2 responsive styling
Completed Task 3 UI recreation
Added HTML structure for Task 1
Improved spacing and typography in Task 2
```

**Avoid meaningless commit messages such as:**

```text
update
changes
done
final
assignment
abc
test
```

Your commit history should reflect the actual progress and work you have done. Do not make meaningless commits just to increase the number of commits.

If you work on different tasks separately, commit meaningful progress separately where appropriate.

---

## Step 10: Push Your Work to Your Own Fork

After committing your changes, push your work to your own GitHub fork.

Execute:

```bash
git push origin main
```

This command pushes your commits to your own fork because `origin` points to the fork you cloned.

**Do not push directly to the original repository.**

After pushing, open your fork on GitHub and verify that:

- Your personal submission folder is visible inside `Students Submission`.
- Your Task 1, Task 2, and Task 3 folders are present.
- Your files have been uploaded correctly.
- Your commit history reflects your changes.

Pushing to your fork does not complete the submission. You must still create a Pull Request.

---

## Step 11: Submit Your Assignment Through a Pull Request

After successfully pushing your changes to your fork, you must submit your work to the original repository through a Pull Request.

### Create your Pull Request

1. Open your own fork on GitHub.
2. On your fork's repository page, click the **Pull requests** tab.
3. Click **New pull request**.
4. GitHub will open the comparison page.
5. Verify that the base repository and branch are correct.

### Verify the following configuration

| Field | Required value |
|---|---|
| Base repository | `prathmesh-ghatmal/Value_Added_Assignment_1` |
| Base branch | `main` |
| Head repository | Your own fork |
| Compare branch | `main` |

This means you are submitting changes from your fork's `main` branch to the original repository's `main` branch.

6. Carefully check the changes displayed on the comparison page.
7. Make sure your submission contains only your own assignment folder and relevant files.
8. Click **Create pull request**.
9. Enter a meaningful Pull Request title using the format below:

```text
Value Added Assignment 1 Submission - FULL ROLL NUMBER - FULL NAME
```

Example:

```text
Value Added Assignment 1 Submission - 2401055 - Prathmesh Ghatmal
```

10. Review your Pull Request details.
11. Click **Create pull request** to submit it.

**Do not merge your own Pull Request.** Submission is complete once your Pull Request has been successfully created.

---

## Final Submission Checklist

Before submitting, ensure that you have completed every item below:

- [ ] I have read the entire README and understood all instructions.
- [ ] I forked the original repository using the prescribed Fork workflow.
- [ ] I kept the repository name unchanged.
- [ ] I cloned my own fork, not the original repository.
- [ ] I created my submission folder inside `Students Submission`.
- [ ] My folder follows the exact `ROLL_NUMBER_FIRSTNAME_LASTNAME` naming convention.
- [ ] I created `Task 1`, `Task 2`, and `Task 3` folders.
- [ ] Each task contains `index.html` and `style.css`.
- [ ] I completed all three tasks using HTML and CSS only.
- [ ] I did not use AI tools to generate, write, modify, or debug my code.
- [ ] I did not copy code from other students.
- [ ] I added meaningful comments explaining my implementation.
- [ ] I checked my code and tested all tasks in a browser.
- [ ] I used meaningful commit messages.
- [ ] I committed my work and pushed it to my own fork.
- [ ] I created a Pull Request to the original repository's `main` branch.
- [ ] I verified that my Pull Request contains only my own submission.

---

# Submission Is Not Complete Until Your Pull Request Is Created

Simply completing the tasks, committing the code, or pushing it to your fork is **not sufficient**.

You must successfully create a Pull Request against the original repository following the exact procedure described in this README.


Failure to follow the prescribed workflow, naming convention, folder structure, or assignment rules may result in your submission not being evaluated.
