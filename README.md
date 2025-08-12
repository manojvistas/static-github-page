# 🌐  Host a Static Website with GitHub Pages

## 📌 Objective
Deploy a simple HTML website using **GitHub Pages**.

---

## 🛠 Tools Used
- **GitHub** – for version control and repository hosting  
- **GitHub Pages** – for free static website hosting  
- **VS Code** – for editing HTML and CSS  

---

## 📂 Project Structure
my-static-site/
│
├── index.html # Main HTML file
└── README.md # Project documentation


---

## 🚀 Deployment Steps

### 1️⃣ Create HTML File
1. Open **VS Code** (or any text editor).  
2. Create a file named `index.html`.  
3. Add sample HTML content:
```html

2️⃣ Push to GitHub
Create a new GitHub repository (public).

Open terminal in your project folder and run:


git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
3️⃣ Enable GitHub Pages
Go to Repo → Settings → Pages.

In Source, select:

Branch: main

Folder: / (root)

Click Save.

4️⃣ Get Live Website Link
After a few seconds, your website will be live at:


https://<your-username>.github.io/<repo-name>/
5️⃣ Optional: Add CSS
Create a file named style.css:


Link it in your HTML:


<link rel="stylesheet" href="style.css">
Push changes to GitHub:


git add .
git commit -m "Added CSS styling"
git push
📸 Project Output

✅ Outcome
Learned how to deploy static content for free using GitHub Pages.

Created and hosted a personal HTML website.

🔗 Live Demo
View Website Here

📜 License
This project is licensed under the MIT License.








Ask ChatGPT
