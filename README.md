# How to host a resume on GitHub

There is a demo of a resume make by static website and host on GitHub

[Publishing to Git](resume.gif)

## Purpose

This project aims to help you host your resume on GitHub and follow the concepts in Andrew Etter's book Modern Technical Writhing. In this README, you will learn all the necessary tools and the installation processes of how to make a static website for your resume.

## Audience 

This README is to show Computer Science students how to host a resume on GitHub by using the necessary tools.

## Prerequisites

- #### Markdown

  Markdown is a markup language that can be written by a common text editor. Through simple markup syntax, it can make common text content and a certain format; and for GitHub, we will choose GitHub format. Also, this is a [tutorial](https://www.markdowntutorial.com/) for how to use Markdown because it is easy to learn and highly recommended.

- #### Markdown Editor

  There are many Markdown Editor on the internet, like Typora, Atom, VScode or MarkdownPad.

  For this file, we use [Typora](https://typora.io/) because it is easier to use, and their website designs are great!

- #### GitHub Account

  If you want to post a resume on GitHub, you need to have a GitHub account to use the GitHub Pages.

- #### Jekyll

  Jekyll is a simple static website generator for generating individual, project and organization websites.

- #### Resume 

  Use Markdown to write a resume. If you have no idea how to start it, there are many templates on the GitHub, check what other people do is a good way to learn.

  

## Instructions

1. #### Create a Repository

   - For the Repository Name, we normally use **your-username.github.io**. For example the username for this project is **stonelaiz**, then the name of repository should be **stonelaiz.github.io**
   - Choose **public** or **private** for repository, notice that **private** is only for the **repository**, the static website for **resume** will be **public** after **publish**.

2. #### Upload your Resume into Repository

   - Drag and drop the resume into the repository, remember to click the commit changes button after upload complete.

3. #### Setup the GitHub Pages

   - Go to `Settings > Options > Github Pages`.

   - Choose the **main/master** from the source, then click Save.

   - Refresh the website, now there is a  notice link shown below in the GitHub pages.

     ```
     Your site is ready to be published at https://your-username.github.io/
     ```

   - After a few minutes, new notice link shown below will show in the GitHub pages, now this website is available for viewing.

     ```
     Your site is published at https://your-username.github.io/
     ```

   ![](C:\Users\Josh\Desktop\新建文件夹 (6)\resume\GitHub-pages.gif)

4. #### Choose Theme

   - Go to `Settings > Options > Github Pages`.
   - Choose a Theme that based on Jekyll

5. #### Modify Website Locally

   - Choose repository from **GitHub Desktop** that you want to modify, clone them on your desktop.

   - Open resume by clicking `Open in Typora` or if your use other editor, it should be `Open in YourEditor`

     ![](C:\Users\Josh\Desktop\新建文件夹 (6)\resume\open in markdown.gif)

   - Now you can change the resume by **Typora** 

   - After you save your modification, you can check what you have modified and the modify history by using **GitHub Desktop**

     ![](C:\Users\Josh\Desktop\新建文件夹 (6)\resume\history.gif)

6. ####  Upload the Modified Website

   - Click the `Commit to main` at left bottom of GitHub Desktop
   - Click `Push origin` in next pages.

   ![](C:\Users\Josh\Desktop\新建文件夹 (6)\resume\upload.gif)

## Principles of Andrew Etter

#### Using static webpages 

- For programmers, they often read and publish technical materials on the internet, so a simple, fast and portable website is what they need, and this is what a static website can do. You can host them anywhere without a database and it contains a lot of setup processes. 

#### Using a Lightweight Markup Language

- A lightweight markup language with a static site generator is necessary for technical writers. It can quickly convert the documents into HTML. With Lightweight Markup Language, people can quickly create a static website without learning any HTML knowledge. 

- Compared to HTML, Lightweight Markup Language is simpler and  human-readable, so it is more efficient. 

#### Using Distributed Version Control System

- A distributed version control system is a method of file version control, which allows different developers to make changes to software or files at the same time without affecting each other. It can be operated offline and locally.
- For this README, we can use **GitHub Desktop** to control the version. **Git** is also a good way to do this job. However, for people who are novices to Distributed Version Control System, visual software may be easier to use than Terminal.



## More Resources

A quick and free guide to getting started with Markdown: [Markdown tutorial](https://www.markdowntutorial.com/)

A comprehensive and free guide to modern technical writing: [Etter, Andrew. Modern Technical Writing. Kindle edition, Self-published, 2016.](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

A detailed introduction to the Markdown editor: [The 10 Best Markdown Editors of 2020](https://www.shopify.ca/partners/blog/10-of-the-best-markdown-editors)

## Acknowledgements

**Author**: [Zijian Lai](https://github.com/stonelaiz)

**Group Member:**

- Eriq Hampton

- Nicholus Bittner

**Template** from [jzj1993](https://github.com/jzj1993)

**Some fonts, icons, etc.** come from: [CyC2018](https://github.com/CyC2018/Markdown-Resume), [billryan](https://github.com/billryan/resume)

Thanks for [**Andrew Etter's book: Modern Technical Writing. Kindle edition, Self-published, 2016.**](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## FAQs

Q: Why is Markdown better than a word processor?

A: For the programmers, the Markdown is better than a word processor, and reasons are shown below:

			1. Markdown can help you focus on your text content instead of typography.
			2. Markdown can easily export PDF, HTML and md file
			3. Markdown is plain text content, compatible with all text editors and word processing software.
			4. Modify your article version at any time, no need to generate several file versions like word processing software which causes confusion.
			5. Readable, intuitive and low cost of learning.

Q: Why is all my whitespace in Markdown is not showing up?

A: If you type sequential whitespace, most Markdown editor will ignore them and it will show in the editing view, but if you try to print your file or export it, all whitespace will be ignored.

​		There are two ways to solve this problem:

            1. Put "\" before every whitespace, it can escape whitespace
            2. Use HTML entity $nbsp

   	Both ways are only available in Source Code Mode.



