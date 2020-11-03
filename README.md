# How to host a resume on GitHub

------



## Audience 

If you are a Computer Science student and you are trying to post your resume on GitHub, then this document may be able to help you 



## Prerequisites

- #### Markdown

  Markdown is a markup language that can be written by a common text editor. Through simple markup syntax, it can make common text content and a certain format; and for GitHub, we will choose GitHub format. Also, this is a [tutorial](https://www.markdowntutorial.com/) for how to use Markdown because it is easy to learn and highly recommended.

- #### Markdown Editor

  There are many Markdown Editor on the internet, like Typora, Atom, VScode or MarkdownPad.

  For this file, we use [Typora](https://typora.io/) because it is easier to use, and their website designs are great!

- #### GitHub Account

  If you want to post a resume on GitHub, you need to have a GitHub account.

- #### [GitHub Pages](https://pages.github.com/)

  GitHub Pages is a web hosting service provided by GitHub. It can be used to store static web pages, including blogs and project documents. Generally, the GitHub Pages website uses the subdomain name of github.io.

- #### Jekyll

  Jekyll is a simple static website generator for generating individual, project and organization websites.



## Get to Start

1. #### Prepare a Resume

   Use Markdown to write a resume. If you have no idea how to start it, there are many templates on the GitHub, check what other people do is a good way to learn.

2. #### Create a Repository

   As Etter says in his book, we need to use a distributed version control system (DVCS) like Git and Mercurial, so we will use GitHub in this tutorial. 

   1. In your GitHub Homepage, click the drop-down button in the upper right corner.

   2. In the Repository Name, we normally use yourusername.github.io. 

      For example, if your username is Tom,  you repository name should be 

      ```
      tom.github.io
      ```

      remember the username must be lowercase.

      ![]()

   3. Then, you can choose public or private for your repository. 

      but, note that even if you choose private after your publish the GitHub Pages, the Pages is public.

   4. You can choose to add a README file if you want to explain your project.

   5. Click Create repository, now you have your first repository in your life.

3. #### Upload your Resume into Repository

   1. Drag and drop your resume into the repository, remember to click the commit changes button after you upload.

4. #### Setup the GitHub Pages

   1. Click the setting button, at the bottom of pages you can find the GitHub Pages, 
   2. Choose the main or master from the source, then click Save.
   3. Then refresh the website, now you can see the notice in the GitHub pages.
   4. After a few minutes you can check the website you set before, now it should be available for views.

5. #### Make Static Websites

   From Etter's book, we also need Make a Static Websites. In fact, in the last step we already make a static websites. GitHub uses Jekyll to process your file to into static websites, but it is not good enough, we still need to use Jekyll individual to make your websites look better.

      1. Setup Jekyll, If you have no idea how to do that, I will put a tutorial at the end of this file.

      2. Choose a Theme, maybe you are already noticed that you can choose Jekyll Theme when you setup the GitHub pages, 

         

6. #### Resource

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

