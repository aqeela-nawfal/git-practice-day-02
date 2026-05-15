# Day 2 PowerShell Commands

Run these commands from this folder:

```powershell
cd C:\Users\USER\Desktop\INTERN\Week-01\Day-02-Git-Practice
```

## Start Git

```powershell
git init
git status
git add .
git commit -m "chore: add day 2 git practice starter"
```

## Connect To GitHub

Create a GitHub repository named:

```text
git-practice-day-02
```

Then connect it:

```powershell
git remote add origin git@github.com:aqeela-nawfal/git-practice-day-02.git
git push -u origin main
```

## Feature Branch 1

```powershell
git checkout -b feature/readme-improvements
git status
git add .
git commit -m "docs: improve day 2 README"
git push -u origin feature/readme-improvements
```

Open GitHub and create a Pull Request from `feature/readme-improvements` into `main`.

## Feature Branch 2

```powershell
git checkout main
git pull origin main
git checkout -b feature/html-structure
git status
git add .
git commit -m "feat: improve HTML structure"
git push -u origin feature/html-structure
```

Open GitHub and create a Pull Request from `feature/html-structure` into `main`.

## Feature Branch 3

```powershell
git checkout main
git pull origin main
git checkout -b feature/style-page
git status
git add .
git commit -m "style: improve page styling"
git push -u origin feature/style-page
```

Open GitHub and create a Pull Request from `feature/style-page` into `main`.

## Check History

```powershell
git checkout main
git pull origin main
git log --oneline
```
