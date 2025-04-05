

---

```markdown
# Part 3: Merging Changes

After both Tom and Jerry have pushed their changes, you (or another team member) can review and merge these changes into the main project. The process involves:

- Creating a Pull Request
- Merging the Pull Request into the main branch

---

## Understanding Pull Requests

A **Pull Request (PR)** is a feature used in GitHub (and other Git-based version control systems) that allows you to notify team members about the changes you've pushed to a branch in a repository.

Essentially, it's a request to review and pull in your contribution to the main project. Pull requests are central to the collaborative development process, enabling team members to:

- Discuss
- Review
- Suggest changes
- Approve updates

---

## How to Create a Pull Request on GitHub

After both Tom and Jerry have pushed their work to their respective branches, the next step is to create a pull request for each of them.

### Example: Tom Creating a Pull Request

#### 1. Navigate to Your GitHub Repository
Open your web browser and go to the GitHub page for the repository.

#### 2. Switch to the Branch
Click on the branch dropdown near the top left corner and select the branch Tom has been working on, for example, `update-navigation`.

#### 3. Create New Pull Request
Click the **"New pull request"** button next to the branch dropdown menu.

GitHub will automatically set:
- The base branch to `main`
- The compare branch to Tom’s branch

#### 4. Review Tom's Changes
Before creating the pull request, Tom should review his changes. GitHub shows the differences between the base branch and Tom's branch.

#### 5. Create the Pull Request
If everything looks good:
- Click **"Create pull request"**
- Provide a **title** and **description**
- Click **"Create pull request"** again to confirm

---

## Reviewing and Merging Tom's Pull Request

Once the pull request is created, other team members can:

- Review the changes
- Leave comments
- Request modifications

When approved, someone with merge permissions can merge the pull request. This will integrate Tom’s changes from `update-navigation` into the `main` branch.

---

## Jerry's Pull Request: After Tom's Merge

After Tom’s updates are merged, Jerry should now create his PR for the `add-contact-info` branch.

Before doing that, Jerry must **update his branch** with the latest changes from the `main` branch to avoid conflicts.

---

## Updating Jerry's Branch with Latest Changes

### Steps:

#### 1. Switch to Jerry’s Branch
```bash
git checkout add-contact-info
```

#### 2. Pull the Latest Changes from Main
```bash
git pull origin main
```

**Purpose:** This fetches and merges changes from `main` (which now includes Tom’s changes) into Jerry’s branch.

---

## Finalizing Jerry's Contribution

Assuming no conflicts...

#### 1. Push the Updated Branch to GitHub
```bash
git push origin add-contact-info
```

**Note:**  
`origin` refers to the remote repository's default name. It's a shortcut to GitHub's URL.

#### 2. Create the Pull Request
Create a PR for Jerry's changes, just like Tom did.

#### 3. Merge Jerry's Pull Request
Click **"Merge pull request"** to complete the process.

---

## Summary

This simulated workflow shows how Git enables **collaborative development**, allowing multiple developers to:

- Work on different features
- Stay in sync
- Merge seamlessly, even on the same files

