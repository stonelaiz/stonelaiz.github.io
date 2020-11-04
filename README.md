# How to host a resume on GitHub

------

## Purpose

This project aims to help you host your resume on GitHub and follow the concepts in Andrew Etter's book Modern Technical Writhing. In this README, you will learn all necessary tool, and the installation processes of how to make a static website for your resume.

## Audience 

This README is to show Computer Science students how to host a resume on GitHub by using necessary tool.

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

   - For the Repository Name, we normally use **yourusername.github.io**. For example if the username is tom, then the name of repository should be **tom.github.io**
   - Choose **public** or **private** for repository, notice that **private** is only for the **repository**, the static website for **resume** will be **public** after **publish**.

2. #### Upload your Resume into Repository

   - Drag and drop the resume into the repository, remember to click the commit changes button after upload complete.

3. #### Setup the GitHub Pages

   - Go to `Settings > Options > Github Pages`.

   - Choose the **main/master** from the source, then click Save.

   - Refresh the website, now their is a new notice like below in the GitHub pages.

     ```
     Your site is ready to be published at https://your-username.github.io/
     ```

   - After a few minutes, new notice like below will showing in the GitHub pages, now this website is available for view.

     ```
     Your site is published at https://your-username.github.io/
     ```

4. #### Choose Theme

   - Go to `Settings > Options > Github Pages`.
   - Choose a Theme that basic on Jekyll

5. #### Modify Website Locally

   - Choose repository from **GitHub Desktop** that you want modify, clone them in your desktop.

   - Open resume by click `Open in Typora` or if your use other editor, it should be `Open in YourEditor`

   - Now you can change the resume by **Typora** 

6. ####  Upload Modified Website

   - 

   

## Principles of Andrew Etter

#### Using static webpages 

- For programmer, it is often publish and read some technical materials on the internet, so a simple, fast and portability website is what they need, and this is what a static website can do. You can host them at anywhere without database and a lot of setup processes. 

#### Using a Lightweight Markup Language

- A lightweight markup language with a static site generator is necessary for technical writers, it can quickly convert the documents into HTML. With Lightweight Markup Language, people can quickly create a static website without learning any HTML knowledge. 

- Compared to HTML, Lightweight Markup Language is simpler and  human readable, so it is more efficient. 

#### Using Distributed Version Control System

- Distributed version control system is a method of file version control, which allows different developers to make changes to software or files at the same time without affecting each other. It can be operated offline and locally.
- For this README, we can use **GitHub Desktop** to control the version. **Git** is also good way to do this job, but for the people who just learn how to use Distributed Version Control System, a visual software may be easier to use than Terminal



## More Resource

[Markdown tutorial](https://www.markdowntutorial.com/)

[Etter, Andrew. Modern Technical Writing. Kindle edition, Self-published, 2016.](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

[GitHub and Jekyll Tutorial](http://mcace.me/github-pages/jekyll/2018/06/17/use-github-pages.html)

## Acknowledgements

Template from [jzj1993](https://github.com/jzj1993)

Some fonts, icons, etc. come from: [CyC2018](https://github.com/CyC2018/Markdown-Resume), [billryan](https://github.com/billryan/resume)

## FAQs

Q: Why is Markdown better than a word processor?

​	A: For the programmer, the Markdown is better than a word processor, and I have some reasons to support it

			1. Markdown can help you focus on your text content instead of typography.
			2. Markdown can easily export PDF, HTML and md file
			3. Markdown is a plain text content, compatible with all text editors and word processing software.
			4. Modify your article version at any time, no need to generate several file versions like word processing software to cause confusion.
			5. Readable, intuitive and low cost of learning.

Q: Why is all my whitespace in Markdown is not showing up?

​	A: If you type sequential whitespace, most Markdown editor will ignore them and it will show in editing view, but if you try to print your file or export it, all whitespace will be ignored.

​		There are two ways to solve this problem

            1. Put "\" before every whitespace, it can escape whitespace
            2. Use HTML entity $nbsp

   	Both ways are only available in Source Code Mode

