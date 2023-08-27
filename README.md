
Version Control

    In this course, you will learn about how modern software developers collaborate 
    across the world without messing up each other's code. You will look at the different 
    version control systems and how to create an effective software development workflow. 
    You will be introduced to some of the most commonly used Linux commands that you can 
    use to work with files on your hard drive and create powerful workflows that will 
    automate your work, saving you time and effort. Finally, you will see how Git can be 
    used in software development projects to manage team files, you will create a repository 
    that can manage code revisions.


    After completing this course, you will be able to:
    - Implement Version Control systems.
    - Navigate and configure using the command line.
    - Manage code revisions.
    - Create and use a GitHub repository.
    - The modules and resources that you will work through and explore in this course will
    - help you to prepare for the Exam:
    - Below is an outline of the modules that will be covered in this course:

Module 1: Software Collaboration

    In this module, you will learn about using version control or subversion to bring 
    order to the chaos of massive software projects that have the potential for mistakes 
    and bugs. You will look at the different version control systems and how to create an
    effective software development workflow.
    After completing this module, you will be able to:
    Describe how modern software teams collaborate and work on the same codebase.
    List different version control systems and methodologies.
    Illustrate a standard software development workflow.

Module 2: Command Line

    In this module, you will learn how to use the command line to execute commands in Linux. 
    You will be introduced to some of the most commonly used commands that traverse, create,
    rename, and delete files on your hard drive. You will learn how easy it is to use piping
    and redirection to create powerful workflows that will automate your work, saving you 
    time and effort.
    
    After completing this module, you will be able to:
    - Describe how the command line is and how it is used.
    - Practice traversing your hard drive via the command line.
    - Create, rename and delete files and folders on your hard drive using Unix commands.
    - Use pipes and redirection.

Module 3: Git

    This module will help you to develop a strong conceptual understanding of the Git 
    technology and how it is used in software development projects to manage team files. 
    You will install Git, create a local repository, create a commit, create a remote 
    repository and push commits to a remote repository.

After completing this module, you will be able to: 

    Outline the Git principles.
    Use a GitHub repository.
    Describe the steps in a standard GitHub workflow.
    Create branches and merge different branches and sources.
    Describe how code goes from local development to version control and then to live production.

--------------- Module 4: Graded Assessment ----------->

    In the final module, you'll learn about the graded assessment. After you complete the 
    individual units in this module, you'll synthesize the skills you gained from the course 
    to manage a project on GitHub.
    You'll also have to opportunity to reflect on the course content and the learning 
    path that lies ahead.
    After completing this module, you will be able to:
    Recap on all of the topics covered throughout the course.
    Apply all the skills you have learned in a graded project.

--------------  Practical Exercises ------------------->

    We encourage you to complete the practical exercises in this course. By completing these 
    exercises you will have a more practical understanding of how to explore Version Control.

--------------  Example of version control ------------->

    - Subversion
    - Perforce
    - AWS Code Commit
    - Mercurial
    - Git

-----------------Command Line ---------------------------->

    - cd .., cd ~/Desktop  -> Move to place
    - mkdir                -> To create a new folder - mkdir -p dir2/dir3 p for parent
    - touch index.html     -> Create a  new file
    - code example.js      -> Will open the code in VS Code
    - ls                   -> Show the content of a directory
    - ls -l                -> Read and write permission
    - ls -a                -> Show all file even the hiden one
    - pwd                  -> Print working directory
    - cp                   -> Copy file from A to B
    - mv                   -> move file from A to B   -> mv filename directory/
    - rm                   -> Removing a file or directory
    - cat                  -> Allows reading or concatenation of a file
    - less                 -> display the contents of a file one page at the time
    - grep                 -> Global regular expression, allows for searching content of files
    - man ls               -> Give us information about the command ls
    - cd ~                 -> TO navigate to the home directory
    - .bashrc file         -> Configuration
    - .profile             -> Environment variable
    - Press q              -> key to exit
    - vim file.sh          -> Create a new file -> Enter
    - i                    -> Insert mode
    - #!/bin/bash          -> Telling to the OS that this is a bash class
    - echo "Hello world"
    - chmod 755 test.sh    -> Add the permission to the file
    - wc file.txt -w       -> return the number of word in the file

    - Use pipes | command to run multiple commands
 
    - cat > input.txt - ctr d to stop writting cat < input.txt to output the content
    - grep Sam names.txt -> Will return all name with Sam (Case Sensentive)
    - grep -i Sam names.txt
    - grep -w Sam names.txt // Exactly the name Sam


----------------- Git Command ---------------------------->

    - git restore --stage test.txt        -> Remove the file from the staging area
    - git checkout -B 'feature/lesson'    -> Create a new branch
    - git branch                          -> Check the branch

    - We can create a brach, work on it and commit it to create a pull request
    - We can then review the pull request and merge to the main branch after satisfaction
    - git pull command pull the latest code from the codebase
    - git remote -v  to see the connection
    - git checkout main
