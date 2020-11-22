DINO2020/21-E 
Classes 4. Ex.2 Git manual

PLEASE REMEMBER AND FEEL FREE TO CLEAN THE CODE - A PROPER CLEANING IS ALSO A VALID INPUT!
(I AM LEAVING A MESS FOR YOU TO CLEAN UP ]:-)> )

The task is to briefly describe key Git commands (as a group).

Requirements:

    The answer should have the form of a one-file HTML
    All commands from the list below have to be included (description, use and exmple)
    The file should be gramatically correct

How to do it:

    Each student creates their own copy of the repository (fork)
    All changes are made in the student's copy (preferably in the branch per feature model)
    Next, the student sends a Pull Request to the original repository

The exercise is completed when a student:

    made a significant input to the manual (command descripton, manual modification, code review)
    & made their own repository (fork)
    & sent a Pull Request to the original repository

The list of commands to describe. There are 19 of you, so pick one.

        git config --global user.name ""
        git reset HEAD
        gitk -all
        git branch --merged
        git branch "branch" "commit hash"
       
        git pull "remote" "branch"
        git config --global user.email ""
        git diff --staged
        git checkout -b "branch"
        git log --graph --all
        
        git branch -d "branch"
        git fetch "remote" "branch"
        git config --global color.ui true
        git commit "filename"
        git branch -v
        
        git push "remote" "branch"
        git log "branch" --not "branch"
        git bisect (start, bad, good, reset)
        git clone /path/to/repository
        git init
