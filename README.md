# Part 3: Merging Changes

After both **Tom** and **Jerry** have pushed their changes, a team member (like you) can review and merge these changes into the main project. The process involves:

- Creating a Pull Request
- Merging the Pull Request into the main branch

---

## 🧠 Understanding Pull Requests

A **Pull Request (PR)** is a feature used in GitHub (and other Git-based systems) that allows you to **notify team members about changes** you've made to a branch. It's a request to review and incorporate your contributions into the main project.

Pull Requests are essential for collaborative development, enabling peer review, discussions, and conflict resolution before merging.

---

## 🔧 How to Create a Pull Request on GitHub

After Tom and Jerry have pushed their work to their respective branches, here’s how Tom would create a pull request:

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

- Team members can **review**, **comment**, and **approve** it
- Once approved, click **"Merge pull request"** to merge Tom’s changes into the `main` branch

---

## 🔁 Updating Jerry’s Branch with Latest Changes

Before merging Jerry’s work, ensure his branch is **up-to-date** with the latest from `main`.

### Steps:

```bash
# Switch to Jerry's branch
git checkout add-contact-info

# Pull latest changes from main
git pull origin main
