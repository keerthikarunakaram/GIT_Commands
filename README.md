# GIT_Commands

Git is an open-source distributed version control system. It is designed to handle minor to major projects with high speed and efficiency. It is developed to co-ordinate the work among the developers. The version control allows us to track and work together with our team members at the same workspace.

There are 15 basic commands which are used on every day basis:

1. Git init: The git init command is the first command that you will run on Git. The git init command is used to create a new blank repository. It is used to make an existing project as a Git project.

Syntax : 

      $ git init 

  <img width="313" alt="image" src="https://user-images.githubusercontent.com/36369266/193397371-1a218cdc-c77f-417a-a9f6-c0cc1b4933ac.png">
The above command will initialize a .git repository on the desktop. Now we can create and add files on this repository for version control.


2. Git config :  It is a convenience function that is used to set Git configuration values on a global or local project level.

Syntax: 
 
      $ git config –global user.name “[name]”

      $ git config –global user.email “[email address]”

<img width="397" alt="image" src="https://user-images.githubusercontent.com/36369266/193397490-95c3b4f8-2af5-4467-beb7-8260f4a2e16a.png">

3. Git status : The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.

Syntax : 

       $ git status

<img width="433" alt="image" src="https://user-images.githubusercontent.com/36369266/193397810-3c448f6b-d163-4288-a279-59687f4a55f8.png">

4. Git add : The git add command adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit.

Syntax: 
        
       $ git add <filename> // add specific file
  
       $ git add .         // add all the untracked files

<img width="284" alt="image" src="https://user-images.githubusercontent.com/36369266/193397792-4e60d3e8-37bd-4d52-97e1-02b1e6f409ba.png">

5. Git commit : This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
  
  Syntax: 
  
       $ git commit -m <message>
  
  <img width="281" alt="image" src="https://user-images.githubusercontent.com/36369266/193398070-bc88d7d1-2796-4c7b-8b80-7f65acab0754.png">

6. Git List branch : A branch is a version of the repository that diverges from the main working project. This command will list all the branches available in repository.
  
  Syntax : 
  
        $ git branch
  
  <img width="139" alt="image" src="https://user-images.githubusercontent.com/36369266/193398258-931eedbe-68e7-4439-9462-1666a981dd68.png">

 7. Git remote add : When we fetch a repository implicitly, git adds a remote for the repository. Also, we can explicitly add a remote for a repository. We can add a remote as a shot nickname or short name. To add remote as a short name, follow the below command:

Syntax:

        $ git remote add <short name><remote URL>  
      
   <img width="518" alt="image" src="https://user-images.githubusercontent.com/36369266/193398389-12fb39ee-5c83-4ca2-99cc-9bc07814ee18.png">

  8. Git remote -v: Git remote supports a specific option -v to show the URLs that Git has stored as a short name. These short names are used during the reading and write operation. Here, -v stands for verbose.

Syntax:

       $ git remote -v
       
   <img width="376" alt="image" src="https://user-images.githubusercontent.com/36369266/193398564-75df949f-5b9a-478f-a351-52f032328183.png">

  
  9. Git Push : It is used to upload local repository content to a remote repository. If we do not specify the location of a repository, then it will push to default location at origin master.
  
  Syntax:
  
         $ git push <option> [<Remote URL><branch name><refspec>...]  
         
   <img width="338" alt="image" src="https://user-images.githubusercontent.com/36369266/193398712-7b323a17-706e-40a2-b43e-7f7d1b5c1082.png">

  10.Git Create branch : This command will create the new branch.
  
  Syntax : 
  
        $ git branch <branch name>
        
   <img width="215" alt="image" src="https://user-images.githubusercontent.com/36369266/193404707-60c692d6-1134-4820-a14b-604094f5ccd9.png">

  11. Git Checkout :  It lets you navigate between the branches created by git branch.
  
  Syntax : 
  
        $ git checkout <branch name>
        
   <img width="202" alt="image" src="https://user-images.githubusercontent.com/36369266/193404858-686979a7-fd70-4106-852b-99da0d280128.png">

12. Git Merge : The git merge command facilitates you to take the data created by git branch and integrate them into a single branch.
 
 Syntax : 
  
        $ git merge <branch name>
<img width="189" alt="image" src="https://user-images.githubusercontent.com/36369266/193405044-e1a776f2-5008-4c6a-a6da-1f6406cc3855.png">

13. Git log : It is a utility tool to review and read a history of everything that happens to a repository.

Syntax:

        $ git log
 <img width="508" alt="image" src="https://user-images.githubusercontent.com/36369266/193405147-110431b6-7c21-4653-a802-10ffb70ea71e.png">

14. Git Branch delete: It is used to delete the local git branch.

Syntax:

        $ git branch -d <branch name>
  <img width="220" alt="image" src="https://user-images.githubusercontent.com/36369266/193405280-b3290b36-af1b-4e35-8ccb-4dfdc206449e.png">


