# Getting Started

Follow these steps to quickly start working on this project:

1. **Fork the Repository**:
   - Start by [forking this repository](https://github.com/AJLab-GH/docs-templates/fork)
     to your own GitHub account.

2. **Clone the Repository**:

   - Clone the forked repository to your local machine:

     ```bash
     git clone https://github.com/YOUR_USERNAME/docs-templates.git
     cd docs-templates
     ```

3. **Configure your GitHub Pages**:
   - In your `docs-templates` repository settings, navigate
     to `Actions -> Pages` and ensure to set your `Build and Deployment`
     `source` to **Deploy from a branch** and your `branch`to **gh-pages**
     in the **/(root)** folder. Finally, `save` your changes.

   ![GitHub Actions Page Permissions](https://raw.githubusercontent.com/ajlab-gh/docs-template/main/images/page-permissions.PNG)

4. **Configure Gist**:

   - Click the **Settings** gear next to the **About** section

     ![About Section Pages 1](https://raw.githubusercontent.com/ajlab-gh/docs-template/main/images/about-setting1.png)

   - Check `Use your GitHub Pages Website`, and Click `save your changes`.

     ![About Section Pages 2](https://raw.githubusercontent.com/ajlab-gh/docs-template/main/images/about-setting2.png)

5. **Customize your Markdown File(s)**:
   - In this template example, the `actions` and `pages` are configured to use
     your **README.md** file.
     - Open `README.md`.
     - Make your changes

   - After making these changes, commit and push the updated workflow file:

     ```bash
     git add .
     git commit -m "<depict the changes you made>"
     git push origin main
     ```
