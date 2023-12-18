---
layout: default
---

# How to contribute to the wiki page

## Getting started

This tutoral assumes you have the following dependencies installed (only have to isntall them once):

* [Github account](https://github.com/)
* [Git](https://git-scm.com/): a distributed version control system used for tracking changes in source code during software development
* [Ruby](https://www.ruby-lang.org/en/): an open-source programming language that Jekyll was written in
* [Ruby Gems](https://rubygems.org/): package manager for the Ruby programming language. It's used to manage Ruby libraries and dependencies.
* [Bundler](https://bundler.io/): static site generator. It transforms plain text into static websites and blogs, and it's used to build the NBP Lab Wiki.
* [Jekyll](https://jekyllrb.com/): the static site generator that transforms plain text into static websites and blogs, and it's used to build this nbp lab wiki
* [Any code editor](https://code.visualstudio.com/): it is needed for viewing and editing the project files. for example, Visual Studio Code is a popular choice.

For more information on package installation, please refer to this [tutorial](https://www.youtube.com/watch?v=WhrU9m82Wm8&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=2) on YouTube.

### 1. **Github collaboration**
- get added as a collaborator to the [nbp lab wiki github repository](https://github.com/nbplabwiki/nbplabwiki.github.io). as a collaborator, you can clone the repository directly, make changes, and push those changes back to the repository without the intermediate step of a pull request from forking the repository.

### 2. **Set up your local computer environment**

- open a terminal (MacOS users) or command prompt (Windows users) on your local machine.
- clone the repository to your local computer:

   ```
   git clone https://github.com/nbplabwiki/nbplabwiki.github.io.git
   ```
   - note: you may also download the repository as a zip file from [this link](https://github.com/nbplabwiki/nbplabwiki.github.io/) and extract the zip file to your deisred folder.

- navigate to the cloned project directory:
   ```
   cd nbp-lab-wiki
   ```

### 4.**Open repo on using any code editor (e.g. VS Code)** 

### 5. **Familarize yourself with the folder structures**

For more detail information about the default Jekyll folder structure, please refer to this [tutorial](https://www.youtube.com/watch?v=pxua_1vyFck&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=4)

* Project Root (`/`): The main directory where you find the `Gemfile` and essential project files.
* `/_includes/`: Contains common portions of the site used in multiple HTML pages.
* `/_layouts/`: Holds layouts for the site, which are used in HTML pages.
* **`/_posts/`: Stores individual blog posts written in Markdown.**
* `/_sass/`: Includes Sass stylesheets, providing a modular and organized way to manage styles.
* `/assets/`: Contains CSS, JS, and other assets for the site, such as images or fonts.
* `/script/`: Holds scripts or executable files associated with the project.
* **`/slides/`: A folder that stores presentation slides or related materials.**
* `/tags/`: Contains files or data related to categorizing content based on tags.
* `/_config.yml`: Stores site global data and configuration for Jekyll.
* `/.editorconfig`: Contains configurations for text editors using Editorconfig.
* `/.gitignore`: Lists files to be ignored by Git during version control.
* `/Gemfile`: Specifies project dependencies using Bundler.
* **`/index.md`: The homepage of this website, written in Markdown.**
* `/jekyll-theme-minimal.gemspec`: A Gemspec file specifying information about the Jekyll theme as a Ruby gem.
* `/readme.md`: Contains project documentation, providing an overview of the project and its structure.

### 6. **Learn the Git basics**
- to view the lab wiki page on your local computer environment

   ```
   bundle exec jekyll serve
   ```
- copy and paste the server address to your favourite browser. By default it is `localhost:4000`.

### 7. **Create a post on the wiki page**

- Please adhere to existing structure on naming a file in the `_posts` folder
- Some examples here on how to write in markdown: [Markdown examples from the Minimal theme](/MarkdownExamples) and [Markdown example from the Jekyll website](https://aksakalli.github.io/jekyll-doc-theme/docs/cheatsheet/)

### 8. **Publish your changes**

- here are the most useful and relevant git commands:

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
[back](/)