# hello-internet-solutions

# Git Basics

## 1. Create a New Repository
### Using GitHub:
1. Go to [GitHub](https://github.com/).
2. Click the **New** button to create a repository.
3. Enter a repository name and choose visibility (public or private).
4. Click **Create repository**.

### Using Git Locally:
```sh
mkdir my-repo
cd my-repo
git init
```

## 2. Clone an Existing Repository
To clone a repository from GitHub:
```sh
git clone git@github.com:username/repository.git
```
This will create a local copy of the repository.

## 3. Check Git Status
To check the status of your repository:
```sh
git status
```

## 4. Commit Changes
1. Add changes:
   ```sh
   git add .
   ```
2. Commit changes:
   ```sh
   git commit -m "Your commit message here"
   ```

## 5. Push Code to GitHub
1. Add remote origin (if not added):
   ```sh
   git remote add origin git@github.com:username/repository.git
   ```
2. Push to GitHub:
   ```sh
   git push origin main
   ```

## 6. Create a New Branch
To create and switch to a new branch:
```sh
git checkout -b new-branch
```
Push the new branch to GitHub:
```sh
git push origin new-branch
```

---