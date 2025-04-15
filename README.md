# Interactive Quiz App

This is a simple and engaging quiz application hosted on **GitHub Pages**. The app is designed to demonstrate the use of HTML, CSS, and JavaScript while showcasing the process of deploying a static website using GitHub Pages.

## 🌐 Live Demo

[Interactive Quiz App](https://lokesh-matha.github.io/static-website-github/)

---

## 📚 Project Overview

The **Interactive Quiz App** allows users to answer dynamically loaded multiple-choice questions. It's a responsive and user-friendly application styled with modern CSS and Bootstrap.

---

## 🚀 How We Hosted This Project on GitHub Pages

The application was deployed as a static website using **GitHub Pages**. Here's how we did it:

### 1. **Prepare the Project**
   - We created the following files in the project folder:
     - `index.html`: The main HTML file for the quiz.
     - `index.css`: The CSS file for styling the quiz.
     - `index.js`: The JavaScript file for quiz functionality.

### 2. **Create a New GitHub Repository**
   - A new repository was created on GitHub to host the project. 
   - The project files were added to this repository using the following commands:
     ```bash
     git init
     git add .
     git commit -m "Initial commit of Interactive Quiz App"
     git branch -M main
     git remote add origin https://github.com/your-username/quiz-app.git
     git push -u origin main
     ```

### 3. **Enable GitHub Pages**
   - We navigated to the repository’s **Settings** → **Pages** section.
   - Under the **Source** section, the branch was set to `main`, and the folder was set to `/root`.
   - GitHub generated a live site link, which is now our hosted quiz application.

### 4. **Access the Live Site**
   - After enabling GitHub Pages, the live site was accessible at:
     ```
     https://your-username.github.io/quiz-app/
     ```

### 5. **Updating the Site**
   - Any changes to the project are automatically reflected in the live site after committing and pushing updates to the `main` branch.

---

## 🛠️ Tools Used

- **GitHub Pages:** For static website hosting.
- **HTML5:** Structure of the quiz.
- **CSS3:** Styling, animations, and responsiveness.
- **JavaScript:** Functionality to load and manage questions dynamically.
- **Bootstrap 5.3:** Additional styling and responsive design.

---

## 📝 Steps to Customize

1. **Modify Content:**
   - Edit `index.html` for structural changes.
   - Update `index.css` for styling.
   - Add or modify questions in `index.js`.

2. **Deploy Changes:**
   - Push updates to the repository using:
     ```bash
     git add .
     git commit -m "Updated styles or content"
     git push
     ```

3. **Clear Cache:**
   - Perform a hard refresh (`Ctrl + F5`) if changes are not immediately visible.

---

## 🔗 Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

---

Enjoy exploring and hosting with GitHub Pages! 🎉
