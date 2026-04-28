# PLAYWRIGHT TRAINING EXERCISE
## TodoMVC Automation Project

### Objective
The goal of this exercise is to build an end-to-end automated test suite using **Playwright Test** by filling out the missing codes.

### Application Under Test
**TodoMVC Demo Application:** [https://demo.playwright.dev/todomvc](https://demo.playwright.dev/todomvc)

### Exercise Requirements
There are **40 steps** required to complete the test. Refer to each line of the codes in the starter repository.

**Code Repo:** [https://github.com/shawn-thrive/playwright-exercise/blob/main/tests/fill-todo-exercise.spec.ts](https://github.com/shawn-thrive/playwright-exercise/blob/main/tests/fill-todo-exercise.spec.ts)

### Deliverables
* **Green Test Report:** All tests must be passing.
* **GitHub Repository History:** Showing at least 2 Pull Requests and 2 Code Reviews.
* **`fill-todo-exercise.spec.ts`:** (or separate files) following the structure of your finalized code.
* **Demonstration:** A walkthrough of the completed tests.

---

### GitHub Collaboration Workflow

#### Phase 1: The Setup
1.  **The Owner (Partner A):** Create a new fork of the repository in GitHub.
2.  **Invite Partner:** Go to `Settings > Collaborators` and add **Partner B**.
3.  **The Peer (Partner B):** Check your email, accept the invite, and `git clone` the repo.

#### Phase 2: The Work
You will work on separate branches:
* **Partner A:** Run `git checkout -b <branch-name>`
* **Partner B:** Run `git checkout -b <branch-name>`

#### Phase 3: The Merge & Review
1.  **Push:** When your section is done, run:
    ```bash
    git add .
    git commit -m "Completed creation tests or any descriptive message"
    git push origin your-branch-name
    ```
2.  **Pull Request (PR):** A link will appear in your terminal or on GitHub. Open a Pull Request.
3.  **The Review:** Partner A must review Partner B’s code (and vice-versa).
    * *Requirement:* Leave at least one comment or compliment.
4.  **The Merge:** Once the reviewer clicks **Approve**, the owner of the branch can click **Merge Pull Request**.

#### Phase 4: The Sync
Once one partner merges, the other partner's local code is now "outdated."
1.  **Switch to main:** `git checkout main`
2.  **Get the new code:** `git pull origin main`
3.  **Go back to your work:** `git checkout your-branch-name`
4.  **Combine them:** `git merge main`

---

### Cheat Sheet: Git Commands

| Action | Command |
| :--- | :--- |
| **Setup** | `git clone https://github.com/shawn-thrive/playwright-exercise.git` |
| **Stage Changes** | `git add <file>` or `git add .` (for all) |
| **Undo Staging** | `git reset` |
| **Make Commits** | `git commit -m 'descriptive message here'` |
| **List Branches** | `git branch` |
| **Switch Branches** | `git switch <name>` or `git checkout <name>` |
| **Create Branch** | `git switch -c <name>` or `git checkout -b <name>` |
| **Push Changes** | `git push` |
| **Set Upstream Push** | `git push --set-upstream origin <branch-name>` |
| **Fetch Changes** | `git fetch origin main` |
| **Pull Changes** | `git pull` |
