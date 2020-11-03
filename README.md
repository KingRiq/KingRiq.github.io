 # Eriq’s Guide to Hosting a Resume Online.

## Why would I want to host your Resume online?

Well, consider a scenario where you want to impress an employer in hopes that they will hire you. You carefully update your resume and submit it only to realize that you have forgotten information. Unfortunately, it’s too late; the employer has already downloaded your resume` and you now have lost your chance to impress them. 
Static websites mitigate this hassle because you can update them on the fly and when you refer employers to your static website, they will have the most correct and up to date version. 
This readme will provide with instructional information on how to host your resume on GitHub Pages. Following the concepts of Andrew Etter’s book Modern Technical Writing, This README will help provide an understanding of all necessary tools and the installation processes of hosting your website online and hopefully open doors of inquiry about the documentation process.

## Audience
----
The purpose of this tutorial is to show fellow Computer Science students how to host a resume on GitHub Pages. Andrew Etter the author of Modern Technical Writing suggests that as a Technical writer you should invest in a static website


## Prerequisites
----
I will assume that since this document is located online you can get the following necessary tools to get you started.
You will need
* A GitHub account
* 	A terminal, or command line environment, or GitHub’s Desktop Application
* 	A resume formatted in Markdown

## Instructions
----

1. Navigate over to Github.com 
2.	Proceed to log in and create a new repository
3.	Name this new repository username.github.io where username is your actual GitHub username (For example googlefan22.github.io)
o	NOTE: you must follow this exactly or it will not work.
4.	 Choosing whether your resume will be private, or public is entirely up to you but if make it private you will be ignoring the fact that a technical writer aim to produce content that is useful for their audience and Etter expresses that this is the primary goal of technical writing.
5.	Choose whether you are going to use a terminal, or GitHub Application
### Terminal
The following will help you with the process of using terminal with your repository
1.	Open up your terminal
2.	Go to the folder where you want to store your project. This will be your new repository directory.
3.	Clone the directory by putting the following command
git clone https://github.com/username/username.github.io
4.	Enter the project folder by entering cd username.github.io
5.	Click and drag your Markdown formatted resume into the directory and get ready to push it.

**NOTE:** Pushing is the process of adding your file, and documenting why you are adding/editing the file. You are essentially updating the files on a remote repository in GitHub with your local repository on your computer.

6.	Add using the following command and leave a descriptive summary in your commit using git commit -m "Description/Summary"
    >git add --all

    * Typically, since this is your first entry in this repo(repository) you can put something simple like “First commit” or “First Entry” 
 	Etter explains that documentation should be comprehensive so keep this as short but descriptive as you can going forward.

7.	Enter the following command to update your master branch in your repo  and you. Have successfully uploaded your resume. 
    >git push -u origin master 

    
    

    *	This may take a few minutes to actually update. Patience is key.






### GitHub Desktop

The following will help you use GitHub Desktop with your repo(repository).
1.	Click the “Set up in Desktop” button in the quick set up menu within your repository on GitHub.
2.	Save the project once the application opens
3.	Make sure you are in the correct repo within the Desktop App.
4.	Follow the prompts for installation
5.	Enter you project directory 
o	Typically, in your “Documents” folder
6.	Click and drag your Markdown formatted Resume into the directory
7.	Go back to your GitHub Desktop 
8.	Leave a descriptive summary in in the bottom left description box
9.	Click the “commit to master” below the description box
10.	 Click the publish button located on the top right of the Desktop App.

###Finishing up
1.	Open up your web browser.
2.	Navigate to https://username.github.io and you will your resume on display.
3.	Image here



## More Resource
----

Comprehensive and Free guide on how to use Markdown.
https://www.markdownguide.org/
Andrew Etter’s Modern Technical Writing: An Introduction to Software. This book will give
https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
A Descriptive guide to building a static website using Jekyll.
https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages
Jekyll Themes you can apply to your resume using a simple yaml file.
https://pages.github.com/themes/



Authors and Acknowledgement
•	Thanks to Andrew Etter’s Book for creating a comprehensive guide on how to be an efficient technical writer. 
•	GitHub pages for allowing everyone to host a static website free of charge
•	To my teammates in group 7 who provided me with feedback to revise and document this Readme properly.
•	Parker Moore at https://github.com/parkr who is the creator of the slate theme I used for my resume and readme files.
FAQ

Q: Who can access my GitHub repository?
A: Anyone, if your repository is public but only collaborators and those with special permission if you have enabled it private.

Q: Why should I document my commit?
A: Sometimes collaborators need to know the work you have done so they do not recreate the wheel. Overall Andrew Etter explains that short and descriptive documentation provides clarity and being too descriptive can take time away from the technical writer.

Q: Are there any other tools I can use with markdown?
A: Markdown comes in many different flavors according to Etter and depending on the chose can determine what templates you can use. Jekyll themes can be used in conjunction with markdown and you can configure markdown to be integrated with a programming language.

Q: Which is easier to use Desktop App or Terminal.
A: Initially terminal is easier because you copy and paste commands from the start but once you make more updates you will require more sophistication. Documentation conflicts can become problematic. Overall, Desktop is easier to use in the long run.

![Did I do this right](desktopapp)