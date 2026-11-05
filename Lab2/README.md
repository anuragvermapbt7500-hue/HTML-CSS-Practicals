# Lab 2: Pushing and Cloning a Repository

**Name:** Anurag Verma
**Roll No:** 2010303123
**Course:** BCS352 - HTML and CSS Introduction Lab, Invertis University

## Aim

Send your commits to a second repository on your computer and make a copy of it with clone.

## Files

- `index.html`, `style.css` - files used in the repository

## Commands used

```
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v
git push origin main        # use master if git status shows On branch master
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline
```

## Output

![Terminal output](images/screenshot.png)
