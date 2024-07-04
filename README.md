[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15363983&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
This is an online software development platform used for storing, tracking and collaborating on software projects. GitHub supports collaborative software development by allowing developers to collaborates with fellow developers on open-source projects. It has numerous features. These are: easy management, improved safety packages, effectve team managemant among others.


Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it. 
A Github respository is a place where one can store code and files. It can also be private or public.
One can create a Github repository by clicking on profle. Then clicking on repositories. On the upper right corner, click on New repository. One must mention if it's public or private, whether if it's forked, and the last update.


Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
When a team is working on a project, a version control tracks the history of the changes they do on a PROJECT hence they can recover earlier versions of the project. This helps developers to track and manage their software code.



Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Branches allows one to work on new features without affecting the main codebase/ master branch. They facilitate collaboration with other developers and organisation within the projects. They are important for users to experimant and make changes without affecting the master branch. Developers can also work on different features simultaneously on different branches. Lately, branches help developers to test their new features before merging them into the main codebase.
creating a branch 
One can click on the branch button on a repository or use the command  git branch <branch_name> to create a new branch. After making a new branch one can make  changes such as fixing bugs and adding new features.
After making the changes, one must commit the changes. This can be done by using git commit. A descriptive message should also be done about hte changes done.
After commiting the changes, one must puch the changes. One can use git push origin <branch_name>
After pushing, one must merge the branch where changes were made to the main branch. 
One can create a pull request.
or This can be done by using merge commands  git checkout main to switch to the main branch, then git merge <branch_name> to merge the feature branch.



Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
A pull request is a proposal made by developers who have collaborated in a project. The proposals are from the branch to main codebase of a repository. Therefore, developers can review the proposed changes before merging to the main branch.
Developers can also leave comments about the changes they have made
and can therefore discuss before merge.
The steps to create and revew a pull request
First one has to push a branch with the changes to the repository.
Click on pull request
select the branch containg the changes as the head branch. and the main branch as the base branch and compare.
Describe the changes proposed in the pull request and submit by clicking the Create pull request.
reviewing the pull request.
After creating a pull request, developers have have access to the pull request and can examine and propose changes. They can also leave comments like improvements on the project.
Developers then approve the pull request so that the merge may comence. Therefore, the changes are then integrated into th e main branch of the repository.


GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
GitHub Actions allow one to automate tasks within the workflow. 
One can use GitHub Actions to automate tasks:
Continous Integration CI - automatically building and testing your code whenever changes are pushed to the repository
Continous Deployment CD - Automatically deploying code to a server when it passes the CI tests.
An example of a CI/CD pipeline:
1. create a workflow file
2. define the workflow steps
3. commit and push
4. monitor workflow



Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Visual studios is comprehensive Integrated Development Environment IDE. One can use Visual Studios to build apps and websites. The key features include code editor like debugging tools, supports different languages like python etc. 

 Visual studio code is an open-source editor where one can edit code. The features include code editing, debugging tools similar to Visual Studios.
Other differences are Visual studios is more expensive since it is paid while visual studio code is free.
Visual studios has integrates debuggers while those in Visual studio code are basic.



Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
First, copy the code 
Open git bash command line.
Chose where to save e.g Desktop type cd Desktop then cliick enter.
Type git cone and paste the repository from github.
Then type cd and paste the section 
Type Code . and click enter to link Visual studios.
Visual studio will open and from there changes can be made.



Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
Debugging is when one inspects your code by running it step by step to find a programming mistake.
The debugging tools used are:
Breakpoints- This help check for mistakes at particular points. One clicks the margin next to the desired line of code.
Once a breakpoint is hit, you can use various stepping commands:
Step Over,Step Into and Step Out.
Watch windows- This allows one to monitor the values of variables and expressions when coding.
local and autos windows show variables that are being used in the current line of execution.
call stack winndow- locates the source of error by showing the order in which methods and fuctions are called.



Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

developers can clone repositories, commit changes, push and pull from GitHub then manage branches within Visual studios.
Developers can pull requests in GitHub on changes to improve on. They can also use GitHub to track tasks hence keepingg their work/ projects organised.
Real life examples are e-commerse platforms


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
