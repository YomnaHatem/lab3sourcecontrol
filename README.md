 Remove Branches Locally

 git branch -d dev
git branch -d test


Remotely
git push origin --delete dev
git push origin --delete test


How to Delete a Tag Locally 

git tag -d v1.4

 Remotely 

git push origin --delete v1.4


list tag locally
git tag 



What is Git Rebase?
used to reaapply commits from one branch on top of another branch, effectively rewriting the commit history. Keep the project history clean by avoiding merge commits.



A Pull Request is a way for developers to propose changes to a repository. 
It’s a feature in GitHub that make collaboration easier. When you create a pull request, you’re asking others to review and approve your changes before they’re merged into the main branch. This helps ensure that the code is reviewed, discussed, and ready for the project


![image](img.jpg)