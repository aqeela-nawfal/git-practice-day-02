# Day 2 Evidence

## PDF Tasks

- 10 meaningful commits: done locally
- 3 feature branches: done locally
- 3 Pull Requests: pending GitHub repository creation
- Comprehensive `README.md`: done
- Simple merge conflict practice: done locally

## Feature Branches Created

- `feature/readme-improvements`
- `feature/html-structure`
- `feature/style-page`

## Merge Conflict Practice

The branch `feature/conflict-one` was created. The same line in `conflict-practice.txt` was edited on both `main` and the feature branch, then merged into `main` to create a conflict.

Final resolved text:

```text
This line was resolved after practicing a merge conflict.
```

## GitHub Pull Request Step

The local repository remote is configured as:

```text
git@github.com:aqeela-nawfal/git-practice-day-02.git
```

Pushing failed because the repository does not exist on GitHub yet.

To finish the PDF Pull Request requirement:

1. Create a GitHub repository named `git-practice-day-02`.
2. Run:

```powershell
git push -u origin main feature/readme-improvements feature/html-structure feature/style-page
```

3. Open 3 Pull Requests on GitHub:

```text
feature/readme-improvements -> main
feature/html-structure -> main
feature/style-page -> main
```

4. Merge all 3 Pull Requests.
