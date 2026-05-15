# Week 1 Day 2: Git Practice

Goal: practice real Git workflow with commits, branches, pull requests, README writing, and merge conflict resolution.

## Checklist

- [x] Practice 10 meaningful commits with proper commit messages
- [x] Create 3 feature branches
- [ ] Raise 3 Pull Requests and merge them
- [x] Write a comprehensive `README.md` with markdown formatting
- [x] Practice resolving a simple merge conflict

Note: Pull Requests require the GitHub repository to exist online. The local repo is ready, but pushing failed because `aqeela-nawfal/git-practice-day-02` does not exist on GitHub yet.

## Practice Repository

Use this folder as the practice project:

```text
Week-01/Day-02-Git-Practice
```

Recommended GitHub repository name:

```text
git-practice-day-02
```

## Project Overview

This repository is a small Git workflow lab. It is designed to prove that the Day 2 tasks were practiced with real files, real commits, and real branch history.

The project contains:

- A simple HTML page
- A CSS stylesheet
- Git notes
- A merge conflict practice file
- Command references for PowerShell

## Conventional Commit Examples

Use messages like:

```text
docs: add project overview
docs: add installation section
feat: add HTML landing page
feat: add about section
style: add base page styles
style: improve navigation layout
docs: add Git command notes
feat: add contact section
fix: correct heading hierarchy
docs: add learning summary
```

## Repository Owner

- GitHub username: `aqeela-nawfal`
- Practice repository: `git-practice-day-02`

## Suggested 10 Commits

1. Add project README title and overview
2. Add basic HTML page
3. Add semantic header and navigation
4. Add main content section
5. Add about section
6. Add contact section
7. Add base CSS styles
8. Add Git command notes
9. Improve README with setup instructions
10. Add learning summary

## Three Feature Branches

Create these branches one by one:

```powershell
git checkout -b feature/readme-improvements
git checkout -b feature/html-structure
git checkout -b feature/style-page
```

Each branch should include at least one meaningful change and one commit.

## Completion Evidence

When this task is finished, keep these as evidence:

- `git log --oneline` screenshot or copied output
- GitHub repository link
- Pull Request links
- Final `README.md`
- Merge conflict resolution commit

## Pull Request Flow

For each feature branch:

1. Push the branch to GitHub.
2. Open a Pull Request.
3. Review the changed files.
4. Merge the Pull Request into `main`.
5. Pull the latest `main` locally.

Useful commands:

```powershell
git status
git add .
git commit -m "docs: add project overview"
git push origin feature/readme-improvements
git checkout main
git pull origin main
```

## Merge Conflict Practice

Simple practice:

1. Create a branch named `feature/conflict-one`.
2. Edit the same line in `conflict-practice.txt`.
3. Commit the change.
4. Go back to `main`.
5. Edit the same line differently.
6. Commit the change.
7. Merge `feature/conflict-one` into `main`.
8. Resolve the conflict manually.
9. Commit the resolved file.

Commands:

```powershell
git checkout -b feature/conflict-one
git add conflict-practice.txt
git commit -m "docs: update conflict text from branch"
git checkout main
git add conflict-practice.txt
git commit -m "docs: update conflict text from main"
git merge feature/conflict-one
```

When conflict markers appear, edit the file and keep the correct final text.

Conflict markers look like this:

```text
<<<<<<< HEAD
main branch text
=======
feature branch text
>>>>>>> feature/conflict-one
```

Remove the markers after choosing the final version.
