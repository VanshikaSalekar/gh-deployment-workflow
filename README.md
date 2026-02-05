# 🚀 GitHub Pages Deployment Workflow using GitHub Actions

This project demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions. It automatically deploys a static website to GitHub Pages whenever the `index.html` file is updated.

🔗 **Project Page:** [https://roadmap.sh/projects/github-actions-deployment-workflow](https://roadmap.sh/projects/github-actions-deployment-workflow)

🔗 **GitHub Repository:** [https://github.com/VanshikaSalekar/gh-deployment-workflow](https://github.com/VanshikaSalekar/gh-deployment-workflow)

🌐 **Live Website:** [https://vanshikasalekar.github.io/gh-deployment-workflow/](https://vanshikasalekar.github.io/gh-deployment-workflow/)

## 🎯 Project Goal

The main goal of this project is to understand:

- GitHub Actions and workflow automation
- GitHub Pages for static site hosting
- CI/CD concepts and best practices
- Trigger-based deployments
- Automated deployment pipelines

## 📂 Project Structure
```
gh-deployment-workflow/
├── index.html                 # Static website homepage
├── README.md                  # Project documentation
└── .github/
    └── workflows/
        └── deploy.yml         # GitHub Actions workflow
```

## ⚙️ How It Works

1. A change is made to the `index.html` file
2. A push is made to the `main` branch
3. GitHub Actions workflow is automatically triggered
4. The website is deployed to GitHub Pages
5. The updated website becomes live instantly

**Note:** The workflow runs only when `index.html` is modified, ensuring efficient use of CI/CD resources.

## 🧠 Key Concepts Learned

- **Continuous Integration (CI)** - Automatically testing and validating code changes
- **Continuous Deployment (CD)** - Automatically deploying validated changes to production
- **GitHub Actions workflows** - Creating automated workflows with YAML
- **GitHub Pages hosting** - Hosting static websites directly from GitHub repositories
- **Path-based triggers** - Configuring workflows to run only on specific file changes
- **Deployment automation** - Eliminating manual deployment steps

## 🛠️ Technologies Used

- **HTML** - Static website markup
- **Git & GitHub** - Version control and repository hosting
- **GitHub Actions** - CI/CD automation
- **GitHub Pages** - Static site hosting

## 📜 GitHub Actions Workflow Overview

The workflow file (`.github/workflows/deploy.yml`) is responsible for:

- Checking out the repository code
- Configuring GitHub Pages settings
- Uploading website files as artifacts
- Deploying to GitHub Pages

### Workflow Triggers

The workflow triggers only when:

- Changes are pushed to the `main` branch
- The `index.html` file is modified

This ensures efficient resource usage and faster deployment times.

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/VanshikaSalekar/gh-deployment-workflow.git
cd gh-deployment-workflow
```

### 2️⃣ Enable GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Under **Build and deployment**, select **GitHub Actions** as the source

### 3️⃣ Make Changes and Deploy

1. Edit `index.html` with your content
2. Commit and push changes:
```bash
git add index.html
git commit -m "Update website content"
git push origin main
```

3. GitHub Actions will automatically deploy your changes!

## 💡 Future Enhancements (Stretch Goals)

- Add CSS and JavaScript to create an interactive website
- Use a static site generator like Jekyll, Hugo, or Astro
- Add automated testing before deployment (HTML validation, broken link checking)
- Deploy a multi-page website with navigation
- Integrate custom domain support
- Add performance monitoring and analytics
- Implement staging and production environments
- Use Docker for containerized deployments

## 📌 Real-World Applications

This workflow demonstrates essential DevOps practices used in production environments:

- **Automated deployments** reduce human error
- **Version control integration** ensures traceability
- **Fast feedback loops** through automated CI/CD
- **Scalable deployment patterns** applicable to larger projects

## 👨‍💻 Author

**Vanshika Salekar**  
BCA Student & Aspiring DevOps Engineer

## 📜 License

This project is open-source and free to use for educational purposes.

---

⭐ **If you like this project, give it a star on GitHub and fork it to experiment with GitHub Actions!**