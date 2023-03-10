# How to create a hosted website on GitHub pages

## Purpose
#### The purpose of this tutorial is to:
###### 1. Guide you on how to create your own website hosted on GitHub pages
###### 2. Show you how to add a theme to your website
###### 3. Educate on the principles of good technical writing

## Prerequisites 
#### Before starting this tutorial users must first have:
* A resume formatted in Markdown
* A GitHub account
* Know the basics of markdown (If you need some help, check out [this](https://www.markdowntutorial.com) tutorial)
* Have a markdown editor (I recommend [MacDown](https://macdown.uranusjr.com) for mac users)

I won't be going over how to create a proper resume in this guide, but if you need some help there are plenty of online tools that can help!

## Instructions
* For this section, it is assumed that you already have an GitHub account and a resume in Markdown
* If have not already created an account, [here](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) is a tutorial on how to create a GitHub account

### Step one: Creating a repository for GitHub pages
##### 1. Log into your github account 
##### 2. At the top right of GitHub, click the + button, then select "New repository" 
* <img width="251" alt="Screen Shot 2023-03-09 at 2 46 52 PM" src="https://user-images.githubusercontent.com/90879131/224153653-9e8b9125-3cde-429d-b902-9ea7190a8c34.png">
##### 3. Name the repository the same name as your GitHub account
* If you name your repository the same name as your GitHub account, then GitHub will automatically create your website
* <img width="479" alt="Screen Shot 2023-03-09 at 2 48 31 PM" src="https://user-images.githubusercontent.com/90879131/224153983-42e80a73-7d20-47b2-a79a-3cdef11ed404.png">
##### 4. Edit the settings to your liking
* I recommend keeping your repository public so that anybody can see it
* Adding a README is always helpful, even if it just does some simple explanations
* <img width="781" alt="Screen Shot 2023-03-09 at 2 49 39 PM" src="https://user-images.githubusercontent.com/90879131/224154177-bd92eb1f-0488-4eb0-bb9c-af72ca026500.png">
##### 5. Click on "Create Repository" and you are done this step!

### Step two: Uploading your files
* By now you should have:
* A created repository with your GitHub name as its name
* A resume in Markdown language

* Next, we can upload our resume to the repository by following these steps:
##### 1. Save your resume as index.md 
##### 2. Navigate to your created repository 
##### 3. Click on:
* Add file
* Upload file
* <img width="287" alt="Screen Shot 2023-03-09 at 3 04 15 PM" src="https://user-images.githubusercontent.com/90879131/224157535-102cdf97-e8a9-4cc8-b69a-6b04c87226b5.png">
##### 4. Drag your file to upload it
* <img width="575" alt="Screen Shot 2023-03-09 at 3 05 29 PM" src="https://user-images.githubusercontent.com/90879131/224157743-2ce44588-6e73-4390-9650-90fdc98a53e1.png">
##### 5. Select "Commit changes" 

* And your resume is now uploaded to your repository

### Step three: Viewing your website
* In the last two steps you should have:
* Created a GitHub repository
* Uploaded your resume to your repository

* Now, we can view the website hosted on GitHub Pages by doing this:
##### 1. Make sure you are still on the home page for your repository
##### 2. Click the Settings button 
* <img width="482" alt="Screen Shot 2023-03-09 at 3 06 12 PM" src="https://user-images.githubusercontent.com/90879131/224157888-779060cc-95dc-4dc5-9d09-0e4633d2a5f2.png">
##### 3. On the left of you screen, select GitHub Pages
* <img width="941" alt="Screen Shot 2023-03-09 at 3 06 51 PM" src="https://user-images.githubusercontent.com/90879131/224158001-6e47b1b4-42ed-499c-b31f-079f9d08536b.png">

##### 4. Under source, select main as the branch type
##### 5. Your website will then auto generate

##### 6. To view your website, simply click on the link:
* ![Screen Recording 2023-03-09 at 3 10 05 PM](https://user-images.githubusercontent.com/90879131/224162144-1ccdc0b7-ddf9-491e-bdae-316e8594207c.gif)

* Warning: while hosting on GitHub pages is much easier than hosting the website locally, GitHub is sometimes down so you should not rely on it to keep your website constantly active. 

### Step four: Using Jekyll to customize your website
* Using themes is not a necessity, but who wouldn't want their resume to look even better!

* Luckily GitHub pages allows us to add a theme fairly easily, as long as we use one of their [appoved](https://pages.github.com/themes/) themes

* To add a Jekyll theme:
##### 1. Create a new file called config.YML 
##### 2. Upload it to your repository the same way you did to the index.md file
* <img width="829" alt="Screen Shot 2023-03-09 at 3 21 55 PM" src="https://user-images.githubusercontent.com/90879131/224162759-f71eef2c-8d24-4390-9eae-ba250948b904.png">
##### 3. Add the required text to your config.YML file. This _should_ only be one or two lines.
* The required text can be found [here](https://pages.github.com/themes/), just select a theme that you like. 
* For example, I am using the tactile theme, so I added this: remote_theme: pages-themes/tactile@v0.2.0
* <img width="1161" alt="Screen Shot 2023-03-09 at 3 22 01 PM" src="https://user-images.githubusercontent.com/90879131/224162941-29964aa0-2540-4d48-92db-333bf158f69f.png">

* And this is what my resume looks like: 
* <img width="649" alt="Screen Shot 2023-03-09 at 3 23 13 PM" src="https://user-images.githubusercontent.com/90879131/224162974-613bd100-a2e6-4938-9de2-646c2f0eed02.png">


##### 4. Commit the changes

* After commiting the changes, your new theme should be active after a few minutes. 


### Bonus: Principles to keep in mind
* Andrew Etter's [Book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) goes into great detail on topics such as using Markdown or generating static websites. Here are some key takeaways that are useful:

1. Using lightweight langauges (like Markdown) is optimal because they are simple and can be used across all systems. Unlike older tools such as XML, Markdown is easily understandable. This leads to everybody on a team being able to contribute, which is why I used Markdown in this tutorial.

2. For the sample reason (that they are simple) static websites are also perfered. While dynamic websites can be fancy, they are also complicated to set up. Static websites are fairly easy to create, and using a tool such as GitHub pages make it even easier. It is also useful that we can update our website almost instantly. Hosting a website locally is the most optimal, as you have total control. 

### More resources:
* Learn about Markdown: [Markdown tutorial](https://www.markdowntutorial.com)

* Read more about principles of technical communication: [Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

* Read the GitHub pages tutorial: [Github pages tutorial](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account)

* Learn which Jekyll themes can be used on GitHub pages: [List of Jekyll themes](https://pages.github.com/themes/)

## Authors/Ackowledgements
* Author: Jakob McKenna
* Group Member: Zhihao Wang 

* The Jekyll template tactile was used in this tutorial 

* Many concepts of Andrew Etter's [book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) are used throughout this guide

## FAQS

##### 1. Why is Markdown considered better than a word processor? 
* Answer: Markdown is considered better than a word processer for a few reasons:

* It is faster than a word processor
* It is more versitile and can be used over many different systems
* It allows more freedom but is still very simple

##### 2. Can all Jeykell templates can be used on GitHub pages?
* Answer: No. Only certain Jekyll themes are set to work with GitHub pages. To see which ones you can use, click [here](https://pages.github.com/themes/)


