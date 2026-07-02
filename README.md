# Notification System / Engineering Workflow Demo

This project demonstrates a complete Git and GitHub engineering workflow using a notification system as the feature.

## Overview
This repository was created as a hands-on lab to practice and understand a complete Git and GitHub engineering workflow. The project simulates how software teams collaborate on features, review code, and merge changes into a production ready branch. The objective was not to build a complex application but to gain practical experience with the tools and processes used in modern software development.

## Project Purpose
This lab covers: cloning a repo, creating a feature branch, writing and committing changes, pushing to GitHub, opening a Pull Request, code review, squash merging to main, and triggering a CI/CD pipeline via GitHub Actions.

## What Was Accomplished

### 1. Repository Creation
A GitHub repository was created via GitHub CLI to serve as the central location for storing project files and tracking version history.

### 2. Repository Cloning
The repository was cloned to a local machine using GitHub CLI, creating a working copy that could be modified without directly affecting the remote repository.

### 3. Feature Branch Creation
A dedicated feature branch named `feature/add-notification-system` was created. This allowed development work to be isolated from the `main` branch, ensuring that the production-ready code remained stable.

### 4. Code Changes and Commit
A notification configuration file was added covering email, SMS, and push notification channels. A PR description and review comments file were also added. All changes were staged and committed using meaningful conventional commit messages.

### 5. Push to GitHub
The feature branch was pushed to GitHub using `git push -u origin feature/add-notification-system`, making the changes available remotely and ready for collaboration.

### 6. Pull Request Creation
A Pull Request was opened using GitHub CLI with a structured description covering what the PR does, why it was needed, and how to test it.

### 7. Code Review
A review comment file was created simulating real-world feedback. A suggested fix was applied by adding a channel status field to the notification configuration. The fix was committed and pushed back to the feature branch.

### 8. Squash Merge to Main
The Pull Request was merged into the main branch using a squash merge strategy via GitHub CLI. This combined all feature work into a single clean commit and kept the project history organised.

### 9. Branch Cleanup
The feature branch was deleted both remotely and locally after merging to keep the repository clean.

### 10. CI/CD Pipeline
A GitHub Actions workflow was added to demonstrate Continuous Integration. The pipeline triggered automatically on push to main and all steps passed successfully.

## Prerequisites
- Git installed and configured
- GitHub CLI (gh) installed and authenticated
- Terminal access (Windows users: use Git Bash)
- Visual Studio Code
- GitHub Actions

## Getting Started
Clone the repository: git clone <repo-url>
Enter the folder: cd notification-workflow-demo

## Contributing

1. Create a feature branch: git checkout -b feat/your-feature
2. Commit your changes: git commit -m "feat: describe your change"
3. Push the branch: git push -u origin feat/your-feature
4. Open a Pull Request and request a review
5. Apply feedback then merge to main

## Skills Practiced
- Git fundamentals
- Branching strategies
- Conventional commit messages
- Remote repository management
- Pull Request workflow
- Code review process
- Squash merge strategy
- GitHub CLI usage
- Basic CI/CD concepts
- GitHub Actions fundamentals
- Branch cleanup

## Note
A GitHub Actions workflow was implemented to demonstrate Continuous Integration. The pipeline successfully validated the automation process that forms the foundation of a complete CI/CD pipeline.

## License
MIT
