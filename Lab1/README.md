# Lab 1: Starting a Git Repository

**Name:** Anurag Verma
**Roll No:** 2010303123
**Course:** BCS352 - HTML and CSS Introduction Lab, Invertis University

## Aim

Start a Git repository for your lab folder and save your work with commits.

## Files

- `index.html`, `style.css` - files used in the repository

## Commands used

```
mkdir html-lab
cd html-lab
git init
git config --local user.name "YOUR NAME"
git config --local user.email "YOUR EMAIL"
git config user.name
git config user.email
echo "<h1>Welcome to My HTML Lab</h1>" > index.html
git status
git add index.html
git commit -m "Add home page"
echo "<h2>Next meeting</h2>" >> index.html
git add index.html
git commit -m "Add next meeting heading"
git log --oneline
```

## Output

![Terminal output](images/screenshot.png)
