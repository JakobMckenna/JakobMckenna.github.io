# How to create a hosted website on github pages

## Purpose
#### The purpose of this tutorial is to :
###### 1. Guide you on how to create your own website hosted on github pages
###### 2. Show you how to add a theme to your website
###### 3. Educate on the principles of good technical writing

## Prerequisites 
#### Before starting this tutorial users must first have:
* A resume formatted in markdown
* A GitHub account
* Know the basics of markdown (If you need some help, check out [this](https://www.markdowntutorial.com) tutorial)
* Have a markdown editor (I recommend [MacDown](https://macdown.uranusjr.com) for mac users)

I won't be going over how to create a proper resume in this guide, but if you need some help there are plenty of online tools that can help!

## Instructions
* For this section, it is assumed that you already have an GitHub account and a resume in Markdown
* If have not already created an account, [here](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) is a tutorial

#### Step one: Creating a repository for github pages
1. Log into your github account 
2. At the top right of GitHub, click the + button, then select "Create new repository" 
3. Name the repository the same name as your GitHub account
* If you name your repository the same name as your GitHub account, then GitHub will automatically create your website
4. Edit the settings to your liking
* I recommend keeping your repository public so that anybody can see it
* Adding a ReadMe is always helpful, even if it just does some simple explainations
5. Click on "Create Repository" and you are done this step!

#### Step two: Uploading your files
* By now you should have:
* Created repository with your GitHub name as its name
* A resume in Markdown language

* Next, we can upload our resume to the repository by following these steps:
1. Save your resume as index.md 
2. Navigate to your created repository 
3. Click on:
* Add file
* Upload file
4. Drag your file to upload it
5. Select "Commit changes" 

* And your resume is now uploaded to your repository

#### Step three: Viewing your website
* In the last two steps you should have:
* Created a github repository
* Uploaded your resume to your repository

* Now, we can view the website hosted on GitHub Pages by doing this:
1. Make sure you are still on the home page for your repository
2. Click the Settings button 
3. On the left of you screen, select GitHub Pages
4. Under source, select main as the branch type
5. Your website will then auto generate

6. To view your website, simply click on the link:
* (Add pic here)

* Warning: while hosting on GitHub pages is much easier than hosting the website locally, GitHub is sometimes down, so you should not rely on it to keep your website constantly active. 

#### Step four: Using Jekyll to customize your website
* Using themes is not a necessity, but who woulnd't want their resume to look even better!

* Luckily GitHub pages allows us to add a theme fairly easily, as long as we use one of their [appoved](https://pages.github.com/themes/) themes

* To add a Jekyll theme:
##### 1. Create a new file called config.YML 
##### 2. Upload it to your repository the same way you did to the index.md file
##### 3. Add the required text to your config.YML file. This _should_ only be one or two lines.
* The required text can be found [here](https://pages.github.com/themes/), just select a theme that you like. 
* For example, I am using the tactile theme, so I added this: remote_theme: pages-themes/tactile@v0.2.0

* And this is what my resume looks like: 
* ![Picture of resume](file:///Users/jakobmckenna/Desktop/Tut_SS1.png)


###### 4. Commit the changes

* After commiting the changes, your new theme should be active after a few minutes. 


#### Extra: Principles to keep in mind
* Using Markdown is good because 

#### More resources:
*Learn about Markdown: [Markdown tutorial](https://www.markdowntutorial.com)

*Read more about principles of technical communication: [Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

*Read the GitHub pages tutorial: [Github pages tutorial](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account)

*Learn which Jekyll themes can be used on GitHub pages: [List of Jekyll themes](https://pages.github.com/themes/)

## Authors/Ackowledgements
* Author: Jakob McKenna

* The Jekyll template tactile was used in this tutorial 

* Many concepts of Andrew Etter's [book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) are used throughout this guide

## FAQS

1. Why is markdown considered better than a word processor? 
Answer: Markdown is considered better than a word processer becuase it is much faster and easier to edit. 

2. How do I see which Jeykell templates can be used on GitHub pages?
Answer: Look at this link to see which templates can be used: 


