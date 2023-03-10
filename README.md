# HOSTING A RESUME ON GITHUB PAGES

## Purpose
#### The purpose of this README is to guide you through the practical steps of how to host and format your resume using Markdown, VS Code, and GitHub Pages ####

## Prerequisites
#### Before you begin, you must have a resume ready. It does not need to be formatted in markdown already. ####

## Instructions


### Step 1: Download a markdown editor
#### Markdown is the most widely used lightweight markup language in the world. It also has the cleanest syntax. Markdown syntax is easy to use . It also allows you to create consistent formatting across all your content. Using it for resumes allows one to create a professional looking document that is easy to read and understand. It makes it very easy to update and share your resume with others. ###
    1. Open a markdown editor on your computer.
    2. Create a new file and name it "resume.md".
    3. Write your resume content using Markdown syntax. If you're new to Markdown, you can use the Mastering Markdown tutorial to learn the basics.
    4. Save the file.



### Step 2: Install GitHub Desktop and Jekyll ###
#### Jekyll is the most popular static site generator. It allows you to customize your site and differentiate your content from the thousands of ugly, disorganized sites of the world. Jekyll generates static HTML files which are fast, making your resume load faster. You also do not need a backend database for jekyll which reduces security risks. Overall Jekyll is the best choice for hosting your resume if you seek a fast and easy to use static website generator. ####
#### To begin, you'll need to install Visual Studio Code and Jekyll. Follow these steps: ####

    1. Download and install Github Desktop
    2. Install the Jekyll.


### Step 3: Create a GitHub Pages repository ###
#### Github is a form of a distributed version control system (DVCS). They are important to technical writing because developers prefer them. It allows you to keep track of the changes you make to your resume overtime, meaning you can easily revert to to an older version of your resume if needed. ####
#### Next, create a GitHub Pages repository to host your resume. Follow these steps: ####
    1. Sign in to your GitHub account or create a new one if you don't have an account yet.
    2. Click the "New repository" button in the upper right corner.
    3. Name your repository with the following format: username.github.io, where username is your GitHub username. For example, if your GitHub username is opensea, then your repository name would be opensea.github.io.
    4. Choose "Public" for the repository type and click "Create repository".



## Step 4: Clone the repository and add your resume ##
#### Storing your documentation is very important. ### 
### Now that you have a repository, clone it to your computer and add your resume. Follow these steps: ###

1.	In your GitHub repository, click the "Code" button and copy the repository URL.
2.	Open Visual Studio Code and press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac) to open the command palette.
3.	Type "Git: Clone" and select it from the list of options.
4.	Paste your repository URL and choose a folder on your computer to clone the repository.
5.	Open your cloned repository folder in Visual Studio Code.
6.	Add your resume to the repository folder as a Markdown file named index.md.



## Step 5: Customize your resume and publish it to GitHub Pages ##
### Now that you have your resume in the repository, you can customize it and publish it to GitHub Pages. Follow these steps: ###

    1. In Visual Studio Code, open your index.md file.
    2. Customize your resume using Markdown syntax. You can use this Markdown cheatsheet as a reference.
    3. Save your changes.
    4. Open the terminal in Visual Studio Code by pressing Ctrl+Shift+~ (Windows/Linux) or Cmd+Shift+~ (Mac).
    5. Run the command bundle exec jekyll serve to build your resume site and preview it locally in your web browser.
    6. If everything looks good, commit your changes and push them to GitHub by typing the following commands in the terminal:

### visualizing hosting your resume on GitHub Pages ###

![Demo]["C:\Users\kwame\OneDrive\Desktop\COMP 3040\DMiPb3oyH5.mp4"]


## More Resources

### You can find a markdown tutorial by using [this link](https://www.markdowntutorial.com/) ###

### [Here](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) is a link to Modern Technical Writing by Andrew Etter ###

### Use [this link](https://pages.github.com/) to see how to use GitHub pages. ###

## Authors 
### I will like to credit my group members Quinn Wong and Xu Zhou ### 
 


## FAQs
### Q: Can I add additional pages to my resume on GitHub Pages or Codeberg Pages? ###
#### A: Yes, you can add additional pages to your resume by creating new Markdown files in your repository and linking to them from your index page. ####

### Q: Is GitHub Pages or Codeberg Pages free to use? ###
#### A: Yes, both GitHub Pages and Codeberg Pages are free to use. However, keep in mind that GitHub Pages is limited to public repositories only. If you want to host a private repository, you will need to upgrade to a paid plan. ####



