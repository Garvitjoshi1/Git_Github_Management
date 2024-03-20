# Git_Github_Management

*Made By Garvit Joshi*

Welcome to the Git and GitHub Management guide! This document will walk you through the process of contributing to a project using Git and GitHub.

## Getting Started

1. **Fork the Repository:** Start by forking the repository to your GitHub account. Click on the "Fork" button at the top-right corner of the repository page.

2. **Clone the Repository:** Clone the forked repository to your local system using the following command:

3. **Create a New Branch:** Create a new branch to make your contribution. Use the following command:

## Making Changes

4. **Move to the Branch:** Switch to the newly created branch using:

5. **Edit Files:** Make the necessary changes to the files in your local repository.

6. **Check Status:** Check the status of the changes using:

7. **Stage Changes:** Add the changes to the staging area using:

8. **Commit Changes:** Commit the changes with a descriptive message using:

9. **Check Status (Again):** Ensure that all changes are committed by checking the status:

## Pushing Changes

10. **Check Remote URLs:** Verify the URLs associated with the repository using:
 ```
 git remote -v
 ```

11. **Add Upstream Repository:** If necessary, add another GitHub repository as upstream using:
 ```
 git remote add upstream <github_link>
 ```

12. **List Branches:** List all branches to ensure you are on the correct one using:
 ```
 git branch
 ```

13. **Final Push:** Push the changes to your GitHub repository using:
 ```
 git push origin BranchName
 ```

Congratulations! You have successfully contributed to the project. Your changes are now available on GitHub for review and merging.
