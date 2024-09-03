## GitHub Repository Creation and Maintenance Report

### Introduction

- Purpose of the repository: store project files and maintain project development
- Brief overview of the project (MapTour): This project aims to develop a map-based travel guide app to help users make and plan travel routes on the map more conveniently.

### Repository Setup

- Username: WuYi-Vee
- Repository Name: MapTour
- Creation Time: 2024-09-02T23:32:29Z
- The process of creating repository: On the Github homepage, I click on the "+" icon int the upper-right corner and select "New repository". Then I fill in the repository name, description and choose visibility (public). Finally, I click "Create repository".

### Maintenance Activities

- create directory “stand-ups” and file "week1.md" on the branch "main"
- create branch "week1" and create file "repository report.md"
- merge branch "week1" and "main"

Synchronize your local Git repository with a remote repository on GitHub (The example of branch "main")：

```bash
git checkout main
git pull origin main
git add .
git commit -m "message of commit"
git push origin main
```

Merge the changes from week1 branch into main branch：

```bash
git checkout main
git pull origin main
git merge week1
git commit -m "message of merge"
git push origin main
```

