# Task6-demo-
Host a Static Website with GitHub Pages

Steps to Deploy
1. Create a GitHub Repository
Go to GitHub
Click New Repository
Name it (e.g., my-static-site)
Choose Public
Check Add a README file (optional)
Click Create repository

2. Add Your HTML Files

You can either:
Upload files directly:
Click Add file > Upload files
Upload your index.html and any other assets (like style.css, images, etc.)
OR use Git:
git clone https://github.com/your-amit1431-star/my-static-site.git
cd my-static-site
# Add your HTML files here
git add .
git commit -m "Initial commit"
git push

3. Enable GitHub Pages
Go to the Settings tab of your repository
Scroll to Pages in the sidebar
Under "Build and deployment", choose:
Source: Deploy from a branch
Branch: main (or master)
Folder: / (root)
Click Save

4. Access Your Live Website
After a few seconds, GitHub will provide a link like:
https://your-amit1431-star.github.io/my-static-site/
Deliverables
Live Website Link:
> https://your-amit1431-star.github.io/my-static-site/
GitHub Repo Link:
> https://github.com/your-amit1431-star/my-static-site
