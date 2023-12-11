---
layout: default
---

## welcome!

welcome to the nbp lab wiki page.

## onboarding

get started working in the nbp lab.

## tea time calendar winter semester 2023-2024

| day          | date              | presenter       |
|:-------------|:------------------|:----------------|
| Thursday     | 25.01.2024        | Shadi Derakhshan|
| Monday       | 29.01.2024        | free            |
| Thursday     | 01.02.2024        | Debora Nolte    |
| Monday       | 01.02.2024        | free            |
| Thursday     | 08.02.2024        | Tracy Sanchez   |


## contribute to the wiki page

1. **get a github account:**
- ask ann to share github account details & add you as a collaborator to the [NBP Lab Wiki GitHub repository](https://github.com/nbplabwiki/nbplabwiki.github.io).
   - This allows you to push changes directly to the repository.

2. **setup your local Environment:**
- method 1:
  - open terminal (if you are using MacOS)
  - create a folder on your computer where you want to store the repository (e.g. nbp-lab-wiki)
  - clone the repository to your local computer:
     ```
     git clone https://github.com/nbplabwiki/nbplabwiki.github.io.git
     ```
   - navigate to the project directory:
     ```
     cd nbp-lab-wiki
     ```
- method 2 (less technical):
   - create a folder on your computer where you want to store the repository (e.g. nbp-lab-wiki)
   - go to the github repository https://github.com/nbplabwiki/nbplabwiki.github.io.git and download it as a zip file
   - move the file to the created folder

3. **install Dependencies:**
   - Ensure you have all necessary dependencies installed.
     ```bash
     # Install Jekyll (if not already installed)
     gem install bundler jekyll

     # Install project dependencies
     bundle install
     ```
4. **open repo on using any code editor (e.g. VS Code or R)**

5. **Familiarzed with the basic folder strucutre**
   - You may create a new Markdown file for your contribution or edit existing pages.
   - Follow the established formatting and structure.
   - you can watch a quick tutorial here too: xxx

4. **Learn the Git basics:**
   - to view the lab wiki page on your local computer
     ```
     bundle exec jekyll serve
     ```
   - copy and past eht url to 

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

- [Link to examples of writing in markdown](/markdown-examples)