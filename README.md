# LabExerciseSix
# Team Project - Static Website

## Team Members
- Nana Yaw Asamoah Ntim
- Member 2
- Member 3
- Member 4

## Project Description
This project is a simple static website demonstrating Git and GitHub workflows. It consists of a landing page that links to individual profile pages for each team member.

## Repository Structure
```
/team-website
│── index.html  # Landing page with links to member pages
│── member1.html  # Profile page for Member 1
│── member2.html  # Profile page for Member 2
│── member3.html  # Profile page for Member 3
│── member4.html  # Profile page for Member 4
│── README.md  # Project documentation
```

## Git Workflow
### 1. Clone the Repository
```sh
git clone <repo_link>
cd team-website
```

### 2. Create a Feature Branch
Each team member should create a feature branch before making changes:
```sh
git checkout -b feature-<your-name>
```

### 3. Add and Commit Changes
Create your profile page and add it to the repository:
```sh
touch memberX.html  # Replace X with your member number
git add .
git commit -m "Added profile page for <your-name>"
```

### 4. Push Changes and Create a Pull Request
```sh
git push origin feature-<your-name>
```
Go to GitHub → **Pull Requests** → **New PR** → Merge your branch into `main` after review.

### 5. Clean Up After Merge
```sh
git checkout main
git pull origin main
git branch -d feature-<your-name>
git push origin --delete feature-<your-name>
```

## Submission
Once all changes are merged, submit the **GitHub repository link** on **Canvas**.
