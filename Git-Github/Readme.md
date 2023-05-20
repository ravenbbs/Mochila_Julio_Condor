
# GIT CHEAT SHEET

This cheat sheet features the most important and commonly
used Git commands for easy reference.


## Authors

- [@ravenbbs](https://www.github.com/ravenbbs)


## Documentation

[Github Education](https://education.github.com/)


### 


- **CONFIG**
    - **git config --global user.name “[firstname lastname]”**
        >set a name that is identifiable for credit when review version history
        
    - **git config --global user.email “[valid-email]”**
        >set an email address that will be associated with each history marker
        

- **SETUP**
    - **git init**
        > initialize an existing directory as a Git repository
        
    - **git clone [url]**
        > retrieve an entire repository from a hosted location via URL
        


- **STAGE**
    - **git status**
        > show modified files in working directory, staged for your next commit

    - **git add [file]**
        > add a file as it looks now to your next commit (stage)

    - **git diff**
        > diff of what is changed but not staged

    - **git commit -m “[descriptive message]”**
        > commit your staged content as a new commit snapshot


- **BRANCH**
    - **git branch**
        > list your branches
        
    - **git branch [branch-name]**
        > create a new branch
        
    - **git checkout [branch-name]**
        > switch to another branch
        
    - **git merge [branch]**
        > merge the specified branch’s history into the current one
        

- **INSPECT**
    - **git log**
        > show all commits in the current branch’s history
 
    - **git log --follow [file]**
        > show the commits that changed file, even across renames

    - **git diff branchB...branchA**
        > show the diff of what is in branchA that is not in branchB


- **UPDATE**

    - **git push**
        > Transmit local branch commits to the remote repository branch

    - **git pull**
        > fetch and merge any commits from the tracking remote branch


- **CHANGES**
    - **git rm [file]**
        > delete the file from project and stage the removal for commit
        
    - **git mv [existing-path] [new-path]**
        > delete the file from project and stage the removal for commit
        
    - **git log --stat -M**
        > delete the file from project and stage the removal for commit
        


