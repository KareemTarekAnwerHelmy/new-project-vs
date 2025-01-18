#kareem tarek anwer

##1. Remove a Branch Locally
    git branch -d branch_name

##2. Remove a Branch Remotely
    git push origin --delete branch_name

##Annotated Tags 
    Use Case: Used for official releases or milestones where detailed metadata and messages are required.

##Lightweight Tags
    Use Case: Used for quick tagging when metadata and messages are not needed.

##When to Use Rebase
    To Maintain a Linear History
        Use rebase when you want to clean up commit history, avoiding unnecessary merge commits and making the history easier to read.
        Ideal for feature branches that are being worked on locally and not yet shared with others.
    To Incorporate Upstream Changes
        When your branch lags behind the upstream branch (e.g., main), 
        rebasing applies your commits on top of the latest upstream changes, ensuring your branch is up to date.

    Before Merging a Feature Branch
        If you want the feature branch to have a clean history without merge commits, 
        rebase it onto the target branch before merging.

##To list all tags
    git tag

##To delete local tags
    git tag -d v1.0

##To delete remote tag
    git push origin --delete v1.0

![EGYPT](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhcDu86-mvr0bpPbgw30kBeNlLnwSC_OCZ9w&s)