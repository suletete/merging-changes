
# Part 3: Merging Changes

After both **Tom** and **Jerry** have pushed their changes, a team member (like you) can review and merge these changes into the main project. The process involves:

- Creating a Pull Request (PR) for Tom's changes.
- Synchronizing Jerry's branch with the latest changes from the `main` branch.
- Merging Jerry's PR into the main branch.

---

## 🧠 Understanding Pull Requests

A **Pull Request (PR)** is a feature used in GitHub (and other Git-based systems) that allows you to **notify team members about changes** you've made to a branch. It's a request to review and incorporate your contributions into the main project.

Pull Requests are essential for collaborative development, enabling peer review, discussions, and conflict resolution before merging.

---

## 🔧 How to Create a Pull Request on GitHub

After Tom and Jerry have pushed their work to their respective branches, here’s how Tom would create a pull request:

### Tom’s Branch - `update-navigation`

---

### 🔹 1. Navigate to the GitHub Repository

Open your browser and go to the **GitHub page** of the repository.

---

### 🔹 2. Switch to the Branch

Click the branch dropdown menu and select the branch Tom worked on — `update-navigation`.

📸 Screenshot:  
![Switching to Tom’s Branch](PR-1.png)  
<img src="./PR-1.png" alt="Switching to Tom’s Branch" width="600"/>

---

### 🔹 3. Create New Pull Request

Click the **"New pull request"** button.

📸 Screenshot:  
![Creating Pull Request](PR-2.png)  
<img src="./PR-2.png" alt="Creating Pull Request" width="600"/>

GitHub will auto-select:
- **Base branch** → `main`
- **Compare branch** → `update-navigation`

---

### 🔹 4. Review Tom's Changes

Review the diff of what was added/modified. This ensures the correct changes are being merged.

---

### 🔹 5. Create the Pull Request

If everything looks good:

- Click **"Create pull request"**
- Provide a **title** and **description** explaining the purpose of the PR

📸 Screenshot of PR Opened:  
![Open PR](PR-3.png)  
<img src="./PR-3.png" alt="Open Pull Request" width="600"/>

---

## ✅ Reviewing and Merging Tom’s Pull Request

Once the PR is open:

- Team members can **review**, **comment**, and **approve** it.
- Once approved, click **"Merge pull request"** to merge Tom’s changes into the `main` branch.

---

## 🔁 Updating Jerry’s Branch with Latest Changes

Before merging Jerry’s work, ensure his branch is **up-to-date** with the latest from `main`. Here’s how you can do that:

---

### 🔹 1. Switch to Jerry’s Branch

Ensure you’re working on **Jerry’s branch** (e.g., `add-contact-info`).

```bash
# Switch to Jerry's branch
git checkout add-contact-info
```

---

### 🔹 2. Pull Latest Changes from Main

Next, pull the latest changes from the `main` branch into Jerry’s branch to ensure it includes all recent updates, including Tom’s work.

```bash
# Pull latest changes from main
git pull origin main
```

---

### 🔹 3. Resolve Any Merge Conflicts (if any)

If there are any merge conflicts between Jerry’s branch and the main branch, Git will notify you. Resolve these conflicts manually by editing the files and choosing which changes to keep. After resolving conflicts, stage and commit the changes:

```bash
# Stage and commit the resolved changes
git add .
git commit -m "Resolved merge conflicts"
```

---

### 🔹 4. Push Jerry’s Updated Branch

After successfully merging the changes from `main` into Jerry’s branch, push the updated branch to the remote repository:

```bash
# Push Jerry's updated branch
git push origin add-contact-info
```

---

### 🔹 5. Create Pull Request for Jerry

Once Jerry’s branch is updated with the latest changes from `main`, you can create a pull request for his branch, similar to how Tom created his PR.

- Go to the GitHub repository and click on **New pull request**.
- Select **Jerry’s branch** (`add-contact-info`) as the compare branch.
- Provide a **title** and **description** for the pull request.

📸 Screenshot of Pull Request Creation for Jerry:  
![Creating Pull Request for Jerry](PR-3.png)  

---

## ✅ Reviewing and Merging Jerry’s Pull Request

Once Jerry’s PR is created:

- Team members can review, comment, and approve it.
- After approval, click **"Merge pull request"** to merge Jerry’s changes into the `main` branch.

---

## Final Thoughts

By ensuring that both Tom’s and Jerry’s branches are kept up-to-date with the latest changes from `main`, conflicts are minimized, and the merging process becomes more efficient. This comprehensive workflow reflects a real-world collaborative development environment in GitHub.

