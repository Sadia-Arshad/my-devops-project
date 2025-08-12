# DevOps Final Year Project – Static Website CI/CD with GitHub Actions

**Author:** Sadia Arshad  
**Repository:** [`my-devops-project`](https://github.com/Sadia-Arshad/my-devops-project)  
**GitHub Actions Workflow Run:** [View Workflow Log](https://github.com/Sadia-Arshad/my-devops-project/actions/runs/16913753015/job/47923084783)  

---

## 📌 Overview
This project is a simple **DevOps CI/CD pipeline** for deploying a **static HTML website** to **GitHub Pages** automatically using **GitHub Actions**.

Whenever code is pushed to the `main` branch, the workflow automatically:
1. Builds (in this case, prepares static files).
2. Deploys the updated site to GitHub Pages without manual intervention.

---

## 📂 Project Structure
```
my-devops-project/
├── index.html               # Home page
├── about.html               # About page
├── README.md                # Project documentation
└── .github/
    └── workflows/
        └── deploy.yml       # GitHub Actions deployment workflow
```

---

## 🚀 Features
- Fully automated deployment to **GitHub Pages** on push to `main`.
- **No manual hosting** – GitHub Pages serves the website.
- Minimal HTML code – perfect for understanding CI/CD fundamentals.
- Uses **peaceiris/actions-gh-pages** for publishing.

---

## ⚙️ How It Works
1. **Commit & push** changes to the `main` branch.
2. GitHub Actions triggers the `deploy.yml` workflow.
3. Workflow:
   - Checks out the repository.
   - Uses `peaceiris/actions-gh-pages` to push static files to the `gh-pages` branch.
4. GitHub Pages serves the latest deployed version.

---

## 🌐 Live Deployment
Once deployed, your site will be available at:  
```
https://<your-username>.github.io/my-devops-project/
```
*(Replace `<your-username>` with your GitHub username)*

---

## 🛠️ Technologies Used
- **HTML5**
- **GitHub Actions** (CI/CD)
- **GitHub Pages** (Hosting)
- **peaceiris/actions-gh-pages** (Deployment Action)

---

## 📜 License
This project is for educational purposes and demonstrates a basic DevOps deployment pipeline.
