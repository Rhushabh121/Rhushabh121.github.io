# Hosting a Resume on a static site

## Purpose
The purpose of this README is to explain how to host and format a resume in a markdown file using software like GitHub pages, and Jekyll. The language that we I be using for formatting my resume is the markup language. In addition, I will be using the general principles of current Technical Writing, which is explained in Andrew Etter’s book “Modern Technical Writing”. 

## Prerequisites 
*	A resume formatted in Markdown.
*	Create an account on [GitHub](https://github.com/), [Tutorial](https://www.wikihow.com/Create-an-Account-on-GitHub).


## Instructions
![Resume](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/resume.gif)


*	### GitHub Pages
*	Static websites are good, it does not have any installation, no database, and nothing else to install. I am using GitHub Pages for hosting my website, which is also suggested by Etter.
    * **Account creation and creating a repository.** 
        1. Create a new repository, the name of the repository should be in this "**Git_user_name.gitgub.io**" format. The username can be found in the right-top corner. However, if you are not able to find, how to access your repository, ![Drop](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/logo.png) check for this logo in your screen. When pressing it will show a dropdown menu, look for the "your repositories" option. This will take you to your repositories, then press on ![new](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/new_repo.png) this button. 
        2. After naming the file, you can put some descriptions for this repository if you want in the description box, as it is optional. 
        3. Set this repository public, so when an employer wants to see your resume, they can access it through the link provided.
        4. Add a readme file, check the box which says “**ADD a README file**”.
        5. Create the repository by clicking on the button “**create repository**”, this was the last step in creating a repository. 
    *	**Adding your resume to the GitHub** 
        *	There are a few ways for adding and creating a file on git-hub, I will be showing one easy way.
            *  **Creating from git-hub** 
                1.  Open the repository that we created, there is an option available of "**add file**", click on this ![Addfile](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/add_file.PNG) option. The option "**Create new file**" will let you create a file, and the option "**Upload files**" will let you upload the file from your device.
                2.	Make sure to use the correct format while naming the new file from the "**Create new file**" option.  
                3.	Add the content to the file.  
                4.	Adding the description is optional however, it is important when doing big group projects for tracking the progress. Press on the ![Commit_new_file](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/commit_new_file_logo.PNG) button and now the file can be seen in the repository.
    *	**Option for editing on GitHub pages**
        1.	Click on the file you want to edit in the repository.
        2.	Navigate the pencil ![Pencil_icon](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/pencil_icon.PNG) icon on the screen, which will be on right-hand side of the screen below the “**go to file**” button.
        3.	Mouseover that icon and it will say edit this file.
        4.	Clicking on that pencil icon, will take you to the edit page.
        5.	The default screen will show you the edit file screen.
        6.	Click in the dialogue box which says “**Name your file…**”, that is the first thing we need to do. Now there are few different formats that we need to keep in mind. For resume, the name of the file should be **index.md**, the README file should be the standard all caps "**README.md**" and the last file which I need is “**yml**” format file, I will explain that format in the Jekyll part.  
        7.	Besides the edit file option there is a ![Preview](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/preview_option.PNG) option for instance, if I do the formatting in markdown then I can see how it will be viewed on the screen in that preview option.
*	### Jekyll
*	For creating a static website locally there are many site generators exits, Jekyll is one of them. I will be using Jekyll only for only adding a theme to my static site, Jekyll is one of the recommendations of Etter for creating static website.
      *  Adding the theme.
          1.	Create a file named “**_config.yml**” that is out first step. The name should be like this ![filename](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/jekyll_file_name.PNG). 
          2.	In my "**_config.yml**" file you will see a line of code, that code is for theme purpose without the yml file there will be no theme. After we are done with all the steps, you will be able to see the resume on a static site.
          3.	When you are done with creating the yml file last thing is to check all the file names.
          4.	Even if you have named it something else it can be changed by editing the file (refer to "GitHub pages” above).

*	### Last checking
*	Check the repository and files inside the repository.
    1.	Name of the repository “git_user_name.github.io” in this format.
    2.	Resume is in the file named “index.md”.
    3.	The name of the yml file is “_config.yml”.
*	### Run the static site 
    1.	Copy the name of the repository and paste in it on any browser (search URL) and now the resume can be seen on the site. 


## More Resources 
* A Markdown tutorial: [Tutorial](https://helloacm.com/markdown-markup-language-quick-tutorial/)

* A link to Etter’s book: [Book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

* Using Jekyll with GitHub pages: [Tutorial](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) 

## Authors and Acknowledgments
* Author
   *  Rhushabh Patel
* Acknowledgments
   *  Brett Lungal
   *  Xianfeng Lang
   *  Sangil Han
   *  Yelizaveta Yashin     
   *  Andrew Etter: [Book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
## FAQs

1. "Why is Markdown better than a word 
processor?"
*  Markdown is very easy to use, with no complicated syntax, very few features, and can easily implement well-formatted content. 

2. "Why is my resume not showing up?"
*  Firstly, check the naming of the repository and files, are they the correct format? Then check if there is an error in the “_config.yml” file.

