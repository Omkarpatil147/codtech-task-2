# CODTECH-TASK-2  
# CI/CD PIPELINE USING GITHUB ACTIONS  

**COMPANY**: CODTECH IT SOLUTIONS  
**NAME**: OMKAR RAJENDRA PATIL  
**INTERN ID**: CT08DM1418  
**DOMAIN**: DevOps  
**DURATION**: 8 WEEKS  
**MENTOR**: NEELA SANTOSH KUMAR  

---

## DESCRIPTION OF TASK

The objective of Task 2 is to set up a CI/CD (Continuous Integration and Continuous Deployment) pipeline using GitHub Actions to automate the deployment process of a web application. CI/CD is a crucial part of the DevOps lifecycle and ensures that code changes are automatically tested, integrated, and deployed without manual intervention.

To begin with, I created a GitHub repository named `codtech-task-2` and cloned it to my local machine. Inside this repository, I created a very basic static website using HTML. The app is stored in a folder called `webapp`, and contains a file named `index.html` which displays a welcome message for the CodTech Internship.

The next step involved setting up GitHub Actions. GitHub Actions allows us to automate workflows directly from GitHub. I created a YAML configuration file at `.github/workflows/deploy.yml`. This file contains a workflow named **"Deploy Web App"** which is triggered every time I push changes to the `main` branch.

In the workflow, I added steps to check out the repository, simulate the deployment by listing files in the webapp folder, and print the contents of the HTML file. Although this setup does not perform an actual deployment to a server, it simulates what a real deployment process looks like. In a real-world project, we could easily extend this to deploy on GitHub Pages, AWS, or Heroku.

After writing and committing the workflow file, I pushed the changes to GitHub. This automatically triggered the GitHub Actions workflow. I verified the steps in the Actions tab and ensured everything was running smoothly.

This task has helped me understand how CI/CD automation tools like GitHub Actions work in practice. It also gave me hands-on experience with writing YAML workflows, managing project structure, and linking repository changes to automated tasks. In a DevOps role, CI/CD pipelines are essential for ensuring fast, consistent, and error-free deployments.

---

## OUTPUT

### 🔹 GitHub Repository:
[https://github.com/Omkarpatil147/codtech-task-2](https://github.com/Omkarpatil147/codtech-task-2)

### 🔹 Files:
- `webapp/index.html`
- `.github/workflows/deploy.yml`
- `README.md`

### 🔹 GitHub Actions Workflow:
- Name: `Deploy Web App`
- Trigger: On push to `main`
- Steps: Checkout, Simulate Deployment

### 🔹 Tools Used:
- GitHub
- GitHub Actions
- YAML
- HTML
