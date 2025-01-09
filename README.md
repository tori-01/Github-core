# Assignment: Core Functions of GitHub

Welcome to the GitHub Core Functions Assignment! This exercise is designed to help you familiarize yourself with the core features of GitHub, including repositories, commits, branches, pull requests, and collaboration.

## Instructions

Follow the steps below to complete the assignment. By the end of the exercise, you will have successfully created, collaborated on, and managed a GitHub repository.

### Part 1: Forking a Repository from an Organization
1. Log in to your GitHub account.
2. Navigate to the GitHub organization provided by your instructor and locate the repository named `github-core-functions-template`.
3. Fork the repository to your own GitHub account by clicking the **Fork** button in the top-right corner.
4. Clone the forked repository to your local machine using the command:
   ```bash
   git clone <your-forked-repository-url>
   ```

### Part 2: Committing Changes
1. Navigate to the cloned repository directory:
   ```bash
   cd github-core-functions-template
   ```
2. Create a new file named `notes.txt` and add the following content:
   ```
   This is a file to track my GitHub learning journey.
   ```
3. Stage and commit the changes:
   ```bash
   git add notes.txt
   git commit -m "Added notes.txt to track GitHub learning journey"
   ```
4. Push the changes to your forked repository:
   ```bash
   git push origin main
   ```

### Part 3: Branching and Pull Requests
1. Create a new branch for adding additional notes:
   ```bash
   git checkout -b feature/additional-notes
   ```
2. Edit `notes.txt` to add the following content:
   ```
   - Learned how to create repositories
   - Practiced committing changes
   ```
3. Stage and commit the changes:
   ```bash
   git add notes.txt
   git commit -m "Added additional notes to notes.txt"
   ```
4. Push the branch to your forked repository:
   ```bash
   git push origin feature/additional-notes
   ```
5. On the GitHub website, create a pull request to merge the `feature/additional-notes` branch into the `main` branch of your forked repository.
6. Review and merge the pull request.

### Part 4: Collaboration
1. Invite a collaborator to your forked repository (use a classmate or a dummy account).
2. Ask the collaborator to:
    - Clone the repository.
    - Create a new branch named `feature/collaborator-notes`.
    - Add their name to `notes.txt` under a section titled "Contributors".
    - Commit and push their changes.
    - Open a pull request to merge their branch into `main`.
3. Review and merge the collaborator’s pull request.

### Part 5: Issues and Project Boards
1. Create a new issue in your forked repository to improve the `README.md` file.
2. Use GitHub's project board feature to track the progress of this issue.

---

## Deliverables

Submit the following as proof of completion:
- A link to your forked GitHub repository.
- A screenshot showing:
    - The merged pull requests.
    - The issue and project board you created.

---

## Grading Criteria

| Task                                  | Points |
|---------------------------------------|--------|
| Forking the organization repository   | 10     |
| Committing and pushing changes        | 20     |
| Creating and merging pull requests    | 30     |
| Collaboration                         | 20     |
| Issues and project boards             | 20     |
| **Total**                             | **100** |

---


 Follow the steps outlined in the [assignment instructions](./).

## Contributors
- Your Name
- Collaborator's Name

