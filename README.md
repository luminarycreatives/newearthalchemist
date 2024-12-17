README: Managing Changes Locally and Deploying via FileZilla

This document focuses on making changes to your WordPress theme, collaborating via GitHub, and deploying updates to the live site using FileZilla.

Step 1: Collaborate Using GitHub Branches

1. What Are Branches?

Branches allow us to work on specific features or sections of the theme without affecting the main branch. This ensures that changes can be reviewed and merged without breaking the theme.

2. Create a Branch

Open GitHub Desktop.

In the top-left dropdown, click Current Branch > New Branch.

Name the branch according to the feature you are working on (e.g., feature-header or feature-footer).

Click Create Branch to switch to the new branch.

Work on your feature in the local theme files.

3. Commit and Push Changes

After completing your work, open GitHub Desktop.

Add a commit message describing your changes.

Click Commit to [branch name].

Click Push origin to upload the branch to GitHub.

4. Create a Pull Request

Go to GitHub and switch to your branch.

Click Pull Request > New Pull Request.

Add a description of your changes and request a review from your teammate.

After approval, merge the branch into the main branch.

Step 2: Keep the Local Site in Sync

When Your Teammate Uploads Changes

Open GitHub Desktop and click Fetch Origin to check for updates.

Switch to the updated branch and click Pull Origin to download the latest changes.

Your local environment will now reflect the latest updates.

Step 3: Deploy the Updated Theme to the Live Site

Using FileZilla

Open FileZilla or another FTP client.

Connect to the live WordPress site using the provided FTP credentials.

Navigate to the wp-content/themes/ folder on the server.

Upload the updated theme folder:

Drag and drop the folder from your local machine to overwrite the existing theme folder on the server.

Test the live site to ensure the changes have been applied correctly.

Best Practices

Use Branches: Always use branches for new features or fixes to avoid conflicts.

Sync Regularly: Frequently pull updates from GitHub to ensure your local environment is up-to-date.

Test Locally: Verify changes on your local WordPress site before deploying to the live server.

Clear Commit Messages: Use descriptive commit messages to track progress and changes effectively.

By following these steps, you can maintain a streamlined and efficient workflow for managing and deploying updates to your WordPress theme.

