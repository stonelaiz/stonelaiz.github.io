# How to host a resume on GitHub

------



## Audience 

If you are a Computer Science student and you are trying to post your resume on GitHub, then this document may be able to help you 



## Prerequisites

- #### Markdown

  Markdown is a markup language that can be written by a common text editor. Through simple markup syntax, it can make common text content have a certain format, and for GitHub, we will choose GitHub format. Also this is a [tutorial](https://www.markdowntutorial.com/) for how to use Markdown, it is easy to learn, highly recommended.

- #### Markdown Editor

  There are many Markdown Editor on the internet, like Typora, Atom, VScode or MarkdownPad.

  For this file we use [Typora](https://typora.io/), because it easier to use, and their website design is great!

- #### GitHub Account

  If you want to post a resume on GitHub, you have to have a GitHub Account.

- #### [GitHub Pages](https://pages.github.com/)

  GitHub Pages is a web hosting service provided by GitHub, It can be used to store static web pages, including blogs, project documents. Generally, the GitHub Pages website uses the subdomain name of github.io.

- #### Jekyll

  Jekyll is a simple static website generator for generating individual, project or organization websites.



## Get to Start

1. #### Prepare a Resume

   Use Markdown to write a resume. If you have no idea how to start it, there are many templates on the GitHub, check what other people do it good way to learn.

2. #### Create a Repository

   As what Etter say in his book, we need use distributed version control system (DVCS) like Git and Mercurial, so we will use GitHub in this tutorial. 

   1. In your GitHub Homepage, click the drop-down button in the upper right corner.

      ![](C:\Users\Josh\Desktop\新建文件夹 (6)\resume\1.gif)

   2. In the Repository Name, we normally use yourusername.github.io. 

      For example, if your username is Tom. then you repository name should be 

      remember the username must be lowercase.

      ```
      tom.github.io
      ```

      ![]()

   3. Then, you can choose public or private to your repository. 

      but, note that even if you choose private, after your publish the GitHub Pages, the Pages is public.

   4. You can choose add a README file if you want to explain your project.

   5. Click Create repository, now you have you first repository in your life.

3. #### Upload your Resume into Repository

   1. Drag and drop your resume into the repository, remember to click the commit changes button after you upload.

4. #### Setup the GitHub Pages

   1. Click the setting button, at the bottom of pages you can find the GitHub Pages, 
   2. Choose main or master from the source. Then click Save.
   3. Then refresh the website, now you can see the notice in the GitHub pages.
   4. After a few minutes you can check the website you set before, now it should be available for views.

5. #### Make Static Websites

   From Etter's book, we also need a Make a Static Websites. In fact in the last step we already make a static websites, GitHub are use Jekyll to process your file to into static websites, but it is not good enough, we still need to use Jekyll individual to make your websites look better.

      1. Setup Jekyll, If you have no idea how to do that, I will put a tutorial at end of this file.

      2. Choose a Theme, may be some of you are notice that you can choose Jekyll Theme when you setup the GitHub pages, 

         

6. #### Resource

   [Markdown tutorial](https://www.markdowntutorial.com/)

   [Etter, Andrew. Modern Technical Writing. Kindle edition, Self-published, 2016.](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

   [GitHub and Jekyll Tutorial](http://mcace.me/github-pages/jekyll/2018/06/17/use-github-pages.html)

## Acknowledgements

Template from [jzj1993](https://github.com/jzj1993)

Some fonts, icons, etc. come from: [CyC2018](https://github.com/CyC2018/Markdown-Resume), [billryan](https://github.com/billryan/resume)



## FAQs

Q: Why is Markdown better than a word processor?

​	A: For the programmer, the Markdown is better than word processor, and I have some reason to support it

			1. Markdown can help you foucus on your text content instead of typography.
			2. Markdown can easliy export PDF, HTML and md file
			3. Markdown is plain text content, compatible with all text editors and word processing software.
			4. Modify your article version at any time, no need to generate several file versions like word processing software to 			cause confusion.
			5. Readable, intuitive and low cost of learning.

Q: Why is all my whitespace in Markdown is not showing up?

​	A: If you type sequential whitespace, most Markdown editor will ignore them, it will showing in editing view, but if you try to print your file or export it, all whitespace will be ignored.

​		There are two way to solve this problem

            1. Put "\" before every whitespace, it can escape whitespace
            2. Use HTML entity $nbsp

   	Both way are only available in Source Code Mode




