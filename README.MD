<h1 align = "center">GitHub Tutorial</h1>

<!-- Table of Content -->
## Table of Contents
<li>
    <a href = "## Introduction">Introduction</a>
</li>

<li>
    <a href = "## Getting Started">Getting Started</a>
</li>

<li>
    <a href = "## Showcasing">Showcasing</a>
</li>

<li>
    <a href = "## References">References</a>
</li>

<!-- Introduction -->
## Introduction 
Git is a free and open-resources distributed Version Control System (VCS) that designed to handle from small to huge projects with ease. And GitHub is the hosting for Git itself. This repository is designed for beginner to start their first repository in GitHub! 

<!-- Getting Started  -->
## Getting Started 
1. First, you need to install Git in your computer. The following link is for you to install Git in your computer. 
- <a href = "https://git-scm.com/">Git Installation</a>
  

2. Once you install your Git, you may check you Git version by verify that Git has succesfully installed in your computer. You may use the commant prompt in your computer to check it by using the following code. 
    ```sh
    git --version 
    ```

3. Finally, go to GitHub to create your first account and we can start to create your first repository in our next session! 
- <a href = "https://github.com/">Link to GitHub</a>
  
<!-- Showcasing -->
## Showcasing 
1. Great! You are now ready to create your first repository. Go to your GitHub profile and create your first repository. (You can name your repository with any name) Next up, open your Visual Studio Code and run your terminal in 'cmd'. 

2. Run the following code step by step in cmd terminal to create your first README.md 
    ```sh
    echo "# testfile" >> README.md
    git init
    git add . 
    git commit -m "first commit"
    git branch -m main
    git remote add "url"
    git push -u origin main
    ```

3. And now you will have a README.md file in your repository. You can now start to edit your README.md file in your Visual Studio Code. Once you satisfied with your README.md file, you need to follow the following step to so called 'upload' your README.md file in your repository in GitHub account. 
    ```sh
    git add . 
    git commit -m "second commit"
    git push 
    ```
<!-- References -->
## References 
* git init = To initialise a git in your GitHub.
* git add . = To add ALL your file into Git. (You can add certain file only by replace the dot with filename)
* git commit -m "first commit" = To capture that you have commit your work into GitHub.
* git branch -m main = To create a main branch for your repository. 
* git remote add "url" = To set up your passpharse for any changes you made in GitHub. Normally we use SSH key as our url as it is more convenient and easy to use. The SSH key can be set up by using command prompt. 
* git push = To push all your work into GitHub. 



