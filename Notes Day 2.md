# Notes for CSCI 2910-001 

# Josiah Truelove

#  Lab for installing Github and Visual Studio, understanding visual studio, and coding standards

###  Week 1 Day 1 Notes:

### **  • Welcome **
Talked about how it is good to take notes because YOU CAN USE THEM ON EXAMS!
You can get the points back on a project if you go back and correct them on turn them in a timely manner. Make sure to not ask about the time it takes to grade. You can also potentially get points back on exams and quizzes, if you think the grade is wrong (question is wrong). You have a lab out there.
Understanding github and github classroom. Uses 3 tutorials from other companies, so that you can learn how to learn using someone else’s system of learning, besides etsu’s cookie cut curriculum essentially. Don’t live in a cardboard box, have health insurance. Basic stuff. You want to be able to live life well. Learn how to code. Make money.


### **  • Syllabus Review **


### ** • Understanding GitHub and Github Classroom **
He can comment on code. And he can also change code and you can accept the changes and let him commit the changes. Github classroom is a good thing to use for professors and teachers. He gives you a classroom link, then you set up your github or connect your current github, and he can see the repository that is assigned to you, so it is like a dropbox/code updater, that you can use to get educated and educate yourself. Repository is a file system. It is a high directory folder, and have as many subdirectories as you want, and root off of that. You can make a repository out of any of them. This is what you are going to submit to your employers as a resume. It shows what code you have done and can potentially do. Instead of having a one drive or a z drive google drive, github is made to have many people working on your code, made to work with committing changes. How do you keep a file all synced up? Do you send it back to the person who originally made the C# file, and then you expect him to update all the code and hope it works by the end of it? How do you keep everything working. If everything was made by 33 people working on one file, how would you keep it updated, synced, and working, plus keep it where it was working and using the same syntax? Github, Github is the solution. Let’s have a file up in the cloud. Git is the operation up in the cloud, that is used to access that file operation, update, and sync.

Github is a version control system (VCS). A way to manage files and directories, track changes over time, recall previous versions, source control is a subset of vcs. It’s in the name, controlling the version of whatever software or website, program, or application you are making. Each update is a new release. It’s just like finding bugs in a video games, and getting the 4th edition of the game, version 4.8374571, that was the version. It’s really easy to grab the base code, each of you work on local machines, then you combine version with a couple of people, then update it, and then start again from the new version of the file. You keep pushing, combine, testers, bring it to management team, launch, crash, get it working again, then perpetuate.

What is git? Created by Linus Torvalds, April 2005. Replaced Bitkeeper to manage Linux Kernel Changes. Command line version control program. Uses checksums to ensure data integrity. Cross-platform. Open source and free. Over 90% (2018 of companies use Git for version control.

Git Distributed Version Control (DVC). No need to connect to central server. Can work without internet connection. No Single Failure Point. Developers can work independently and merge their work later. Every copy of Git repository (repos) can serve either as the server or as a client. Tracks complete history of changes and not versions. Many many programming languages used.

Repository (Repos). Used to organize a single project. Repos can contain folders, files, images, videos, spreadsheets, and any other data constructs. You can have repositories that are used for anything else. Just like a drive, but it is much more versatile. Use Github for word documents, spreadsheets, anything that can get updated. It’s just the same as code though, it’s just like writing a thesis, or writing a book, and updating versions. That’s all you got to do. That’s why git works. All a picture is is just 1s and 0s organized in such a way that it is a picture. Could push a photoshop to the cloud. Might be disastrous, but it could happen.

Branching. Start with a good base for your project. You get all the basics set up, before doing any logical development. You get everything set up, like getting  a notes sheet ready to be filled out. You worked the file structure out on html files for a website, then your css, and then you do after all of that, you can work on your website, why? So that you can get it to a point where you can make incremental changes. It’s not made to just update the entire file by yourself. This way if you were going to revert things, you only have to revert the past say hour of work, instead sometimes you are reverting 16 hours of work at the place you work, and that is expensive in the workplace. C# is open source. You could potentially update it and get a pull request from Microsoft. When you’re working on a project, you’re going to have a bunch of different features or ideas in progress at any given time – some of which are ready to go, and others which are not. Branching exists to help you manage this workflow. Ideas don’t work, delete the branch. Have many different versions of the same problem. Branch.

Main. Master (needs to be struckout). The main starting branch; Every repo has one. This has the latest working commit. Normally, you do not want to make changes directly to this, you want to “branch” off of this and work with a “test” area. Branching is a core concept in Git, and the entire GitHub flow is based upon it. There’s only one rule: anything in the main branch is always deployable. Because of this, it’s extremely important that your new branch is created off main when working on a feature or fix.

You have a main branch and a dev branch. Main branch would be Professor’s ownership. You have project leads. Alec and Matt are project leads. You would give the project leads pull requests on the dev branch. Three groups pulling from the test group. Nine branches working on different things, then project leads push to the dev branch. Then after this, you have new stuff on the dev branch. Until you have fully tested it, don’t push it to the main branch. Meaning you do a pull request to the main branch, which will mean the dev branch will have pushed every that was new onto the main branch, and now the main branch is your dev branch from before.

Commit is when you are ‘committing’ to those changes that you made to the main branch. 

Pull Request. Pull Requests initiate discussion about your commits. Can be done when?

Merge and Deploy. Once your pull request has been reviewed and the branch passes your tests, you can deploy your changes to verify them in production. If your branch causes issues, you can roll it back by deploying the existing main branch into production. Pull Requests preserve a record of the historical changes to your code. This is searchable to find out why things have been done. Keywords help with making historical documents and the changes that occurred. 

Merge Conflicts, do you keep 1, 2, 3, different lines of code on the exact same line of code, which one do you keep? You have to manage merge conflicts. Pull Requests will pull all your requests.

GitHub. A platform to host git code repos. Most popular Git host. Allow users to collaborate on projects from anywhere. Free. He’s good with you branching off of your main. Get your code where you like it. Commit, and merge. Github is an implementation of git. It is a cloud-based version of git. Time machine. It’s cool. Check it out. Gitkraken, GUIfied version of Github.

Note. Sometimes developers choose to place repo on GitHub as a centralized place where everyone commits changes, but it doesn’t have to be on GitHub.

### ** • Syllabus Review **

Visual Studio & Coding Standards:

Visual Studio ((IDE) Integrated Development Environment)

Visual Studio

Solution Explorer

Editor Window

Team Explorer

Squiqqles and Quick Actions

Squigglies in the code. Allow you to correct your errors. If you hover over a squiggle, you see additional information about the error.

A light bulb may also appear in the left margin with actions, known as quick actions, to fix the errors.

Code Cleanup. With the click of a button, format your code, and apply any code fixes suggested by your code style settings, editorconfig conventions, and Roslyn analyzers. Code Cleanup helps you resolve issues in your code before it goes to code review. Currently available for C# code only. .net framework allows you to work between the different languages and use different OS.

Refactoring. Refactoring is the process of modifying code in order to make it easier to maintain, understand, and extend, but without changing its behavior.

Intellisense. Intellisense is a code-completion aid that includes a number of features: List Members, Paramter Info, Quick Info, And Complete word.
Intellisense. List Members. A list of valid members from a type (or namespace) appears after you type a trigger character (for example, a period (.))

Intellisense. Parameter Info.

Intellisense. Quick Info. Quick info displays the complete declaration for any identifier in your code.

Intellisense. Other Info. Complete Word completes the rest of

Intellisense. Troubleshooting. The cursor is below a code error. You might not be able to use Intellisense, if an incomplete function or other error exists in the code above

Visual Studio Search and Definition. Visual Studio can seem overwhelming at times so many menus, options, and properties. Visual Studio seach (Ctrl+Q, CMD.’) is a great way to rapidly find IDE 

Code Snippets. Visual Studio provides useful code snippets that you can use to quickly and easily generate commonly used code blocks. Code Snippets are small blocks of reusable code that can be inserted in a code file using a right-click menu (context menu) command or a combination of hotkeys. 

Expansion snippets and surround-with snippets. In Visual Studio there are two kinds of code snippets: expansion snippets, which are added at a specified insertion point and may replace a snippet shortcut. Surround-with snippets, which are added around a selected block of code.

Read the Coding Standards.
