Markdown# DCIT50: Laboratory Exercise 1 - Git, GitHub, and Branching

**Student Name:** Taylee Henry  
**Course & Section:** DCIT50 - Object-Oriented Programming  
**Institution:** Cavite State University - Main Campus (Indang, Cavite)  
**Location:** Tanza, Cavite  
**GitHub Repository:** [LAB1-TAYLEE](https://github.com/kage049754/LAB1-TAYLEE)

---

## 📌 Project Overview
This repository contains the completed **Laboratory Exercise 1** for **DCIT50**. The project demonstrates practical knowledge of Git version control, multi-branch management, dynamic HTML5 structure, custom CSS grid/flexbox layouts, keyframe animations, and JavaScript DOM interaction.

---

## 🛠️ Step-by-Step Implementation Guide

### Step 1: Git Environment & Configuration
1. Configured global Git user credentials:
   ```bash
   git config --global user.name "Taylee Henry"
   git config --global user.email "kage049754@gmail.com"
Initialized a local Git repository inside the project directory (lab_1_taylee):Bashgit init
Step 2: Baseline HTML Creation & Initial CommitBuilt the initial index.html file containing the core plain HTML structure.Staged and committed the unstyled HTML version:Bashgit add index.html
git commit -m "Initial commit: Plain HTML introduction"
Step 3: Branching Strategy (no-style)Created the no-style branch directly from the initial commit to preserve the unstyled HTML structure:Bashgit branch no-style
Step 4: Webpage Enhancement (main branch)Designed style.css featuring responsive CSS Grid layout, hover transitions, and keyframe animations.Created script.js featuring interactive DOM events (greeting alert window).Expanded index.html with personalized biographical details (Tanza origin, CvSU Main college life, and hobbies: Reading, Watching, and LEGO).Linked style.css and script.js inside index.html.Staged and committed the complete dynamic build:Bashgit add .
git commit -m "Enhance webpage design with hobbies, location, and CvSU info"
Step 5: Remote Linking & GitHub DeploymentLinked the local repository to the GitHub remote URL:Bashgit remote add origin [https://github.com/kage049754/LAB1-TAYLEE.git](https://github.com/kage049754/LAB1-TAYLEE.git)
Renamed the default branch to main:Bashgit branch -M main
Authenticated via VS Code GitHub Integration and pushed both required branches to GitHub:Bashgit push -u origin main
git push -u origin no-style
🌿 Branch StructureBranch NameDescriptionIncluded FilesmainFull dynamic web application with modern layout, styles, and interactive script logicindex.html, style.css, script.js, README.mdno-stylePreserves the original baseline HTML-only structure prior to CSS and JS integrationindex.html