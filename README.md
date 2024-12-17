# **README: Luminary Creatives Workflow**

This guide walks through the process of working with GitHub branches, managing local changes to your WordPress theme, and deploying updates via **Hostinger**.

---

## **Step 1: Collaborate Using GitHub Branches**

### **1. What Are Branches?**
**Branches** allow you to develop specific features or fix bugs without affecting the main codebase. This method ensures that each change is isolated, reviewed, and merged efficiently, preventing errors in the main theme.

---

### **2. Create a Branch**
To work on a new feature or update your WordPress theme:

1. **Open GitHub Desktop.**
2. **Select the Branch** dropdown at the top-left corner.
3. Click on **Current Branch > New Branch**.
4. **Name your branch** (e.g., `feature-header`, `fix-footer`).
5. Click **Create Branch** to switch to the new branch.

> ✨ **Pro Tip:** Naming your branch according to the feature or task you're working on will keep things organized.

---

### **3. Commit and Push Changes**
Once your changes are ready, commit and push them to GitHub:

1. Open **GitHub Desktop** after making changes in the local theme files.
2. Write a **commit message** that clearly describes your changes (e.g., "Updated header design").
3. Click **Commit to [branch name]**.
4. Press **Push origin** to upload the branch to GitHub.

---

### **4. Create a Pull Request**
After pushing your changes, follow these steps:

1. Go to **GitHub** and switch to your branch.
2. Click **Pull Request > New Pull Request**.
3. Add a **description** of your changes and request a **review** from a teammate.
4. After review and approval, **merge** the branch into the **main branch**.

---

## **Step 2: Keep the Local Site in Sync**

### **When Your Teammate Uploads Changes**

1. Open **GitHub Desktop**.
2. Click **Fetch Origin** to check for updates from the remote repository.
3. Switch to the updated branch and click **Pull Origin** to download the latest changes.
4. Your local environment will now reflect the most recent updates.

---

## **Step 3: Deploy the Updated Theme to the Live Site**

### **Using Hostinger's File Manager**

Deploying your updated theme to your live WordPress site using **Hostinger** is easy and doesn't require additional FTP software. Follow these steps:

1. **Log in to your Hostinger account** and go to the **hPanel**.
2. In the **File Manager**, navigate to the `wp-content/themes/` folder.
3. **Upload the Updated Theme:**
   - On the left side of the File Manager, click on the **Upload** button.
   - **Select the theme folder** you want to upload from your local machine.
   - Make sure to **overwrite the existing theme** on the server by selecting the appropriate option when prompted.
4. **Verify the Live Site:**
   - After uploading, visit your WordPress site to confirm that the changes have been applied.

> 🚀 **Pro Tip:** Clear your browser cache to ensure the most up-to-date theme is visible.

---

## **Best Practices**

- **Use Branches**: Always use branches for new features or fixes to avoid conflicts.
- **Sync Regularly**: Frequently pull updates from GitHub to ensure your local environment is up-to-date.
- **Test Locally**: Verify changes on your local WordPress site before deploying to the live server.
- **Clear Commit Messages**: Use descriptive commit messages to track progress and changes effectively.

By following these steps, you can maintain a streamlined and efficient workflow for managing and deploying updates to your WordPress theme.
