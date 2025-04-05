Sure! Here's your updated **Part 3: Merging Changes** write-up, now with your **Google Drive screenshots embedded** as image links:

---

```markdown
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
![Tom Branch](PR-1.png)

---

### 🔹 3. Create New Pull Request

Click the **"New pull request"** button.

📸 Screenshot:  
![Creating Pull Request](https://drive.google.com/uc?id=1Mozv1vDlSad2VP9LijzvH8M-r9UwzX4M)

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
![Open PR](https://drive.google.com/uc?id=1Q256MqqfyI8Z9FrzurTIP-djQzjTArmL)

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
```

✅ This ensures Jerry’s branch includes Tom’s changes, avoiding merge conflicts.

---

## 🚀 Finalizing Jerry’s Contribution

### Push Updated Branch

```bash
git push origin add-contact-info
```

This uploads Jerry’s branch with all updates to GitHub.

---

### Create & Merge Pull Request for Jerry

Now repeat the PR steps for Jerry:

1. Create PR from `add-contact-info` to `main`
2. Review, approve, and **merge**

---

## 📌 Summary

This workflow demonstrates GitHub’s collaborative features:

- Branching for feature development
- Pull Requests for review and integration
- Merging to keep `main` stable and updated
- Updating branches to avoid conflicts

✅ With screenshots and repository actions, this meets the instructor’s practical evidence requirements.

---
```

---

Let me know if you want this exported as a PDF, Markdown file, or added with Jerry's own screenshots if you have those too!
