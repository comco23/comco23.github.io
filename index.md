---
layout: default
---

## welcome!

welcome to the nbp lab wiki page.

## onboarding
are you an intern, HiWi, BSc, MSc, PhD, or Postdoc in the Nbp? here are some useful documents.

* [check in form](/slides/5-check-in-form.pdf)
* [transponder application](slides/3-transponder-application.pdf)
* [a guide to your thesis](/slides/5-check-in-form.pdf)
* [funding transparency statement](slides/6-FundsTransparencyStatement.pdf)
* [conference guide](slides/1-conference-guide.pdf)
* [thesis guide](slides/2-thesis-guide.pdf)
* [check your bachelor's thesis progress](slides/4-BScProgress.pdf)
* [how to give good talks](slides/7-GivingGoodTalks.pdf)
* [guidelines for paper revisions](slides/8-GuidelinesForRevisions.pdf)

## tea time calendar winter semester 2023-2024

| day          | date              | presenter       |
|:-------------|:------------------|:----------------|
| Thursday     | 25.01.2024        | Shadi Derakhshan|
| Monday       | 29.01.2024        | free            |
| Thursday     | 01.02.2024        | Debora Nolte    |
| Monday       | 01.02.2024        | free            |
| Thursday     | 08.02.2024        | Tracy Sanchez   |

## data analysis and management

i probably should know something about how the university machiens work but i don't know anything

## contribute to the wiki page

1. **get a github account:**
- ask ann to share github account details & add you as a collaborator to the [NBP Lab Wiki GitHub repository](https://github.com/nbplabwiki/nbplabwiki.github.io).
- This allows you to push changes directly to the repository.

2. **set up your local environment:**
- Method 1 (Command Line):
   - open terminal (for macOS users).
   - create a folder on your computer where you want to store the repository (e.g., nbp-lab-wiki).
   - clone the repository to your local computer:
         ```
         git clone https://github.com/nbplabwiki/nbplabwiki.github.io.git
         ```
       - navigate to the project directory:
         ```
         cd nbp-lab-wiki
         ```
- Method 2 (less technical):
   - create a folder on your computer (e.g., nbp-lab-wiki).
   - download the repository as a zip file from [this link](https://github.com/nbplabwiki/nbplabwiki.github.io/).
   - extract the zip file to your created folder.

3. **install necessary dependencies:**
   - ensure you have all necessary dependencies installed.
     ```bash
     # install Jekyll (if not already installed)
     gem install bundler jekyll

     # install project dependencies
     bundle install
     ```
4. **open repo on using any code editor (e.g. VS Code or R)**

5. **familiarzed with the basic folder strucutre**
   - _config.yml: this YAML file contains configuration settings for your Jekyll site. You can define various settings, such as the site title, description, and default layout.
   - index.md: this filerepresents the content of your site's homepage.
   - _posts: this the folder where all the blog posts are stored.
      - Example File: 2023-01-01-welcome-to-the-wiki.md
      - you can create a markdown file here
      - [Link to examples of writing in markdown](/markdown-examples)
   - _layouts: this folder contains layout templates. Layouts define the structure of your pages. For example, you might have a default layout (default.html) and a post layout (post.html).
   - _includes: this folder holds reusable components or snippets that can be included in your layouts or pages.
   - _assets: this folder is used to store your static assets, such as images, stylesheets, and JavaScript files.

4. **Learn the Git basics:**
   - to view the lab wiki page on your local computer
     ```
     bundle exec jekyll serve
     ```
   - copy and paste the server address to your local browser to preview

   - familiarize yourself with basic Git commands:
     ```bash
     # Check the status of your changes
     git status

     # Add changes to the staging area
     git add .

     # Commit changes
     git commit -m "Your commit message"

     # Push changes to GitHub
     git push origin main
     ```