# Git-Github

Git- distributed version control system (DVCS) initially designed and developed by linux Torvalds or Linux kernel development.

VCS(Version control system) - software that helps software developers to work together and maintainn a complete history of their work.

(add someonline defination in better way)

---
Two type of version control system (VCS)
1) CVCS - centralized Version control system - it used a central server to store all files and enables team collaboration. But the major drawback of CVCS is its single point of failure i.e. failure of the central server.
3) DVCS - Distributed Version control system - it does not rely on central server and that is why you can perform many operations when you are offline. you require network connection only to publish your changes and take the latest changes.
---
POV: git belong to distributed version control system.
---

A typical VCS uses somthing called TWO-THREE archetecture, this is what a lot of other VCS use apart from git.
Usually, a VCS works by having two places to store things:
1) Working Copy
2) Repository

Working copy is the place where you make your changes. whenever you edit somthing, it is saved in working copy.

Repository is the place where all the version of files or commits, logs etc is stored.
---
Checking oUt = checking-out is the process of getting files from repository to your working copy. This is because you can only edit files when it is on your working copy. When you are done editing the file, you will save it back to the repository by committing it.

Commiting = Committing is the process of putting back the files from working copy to repository.
---
@2-tree architecture
![images](https://github.com/user-attachments/assets/7d60aa30-7fe0-41da-8e47-0a724e786a97)
This architecture is called 2 tree architecture. Because you have two tree in here, Working copy and repository (SVN - Subversion)

@3-Tree architecture
![download](https://github.com/user-attachments/assets/206a9021-7046-4eb4-9410-2caa27d2ee73)
Git uses three trees, well interestinglt git also has working copy and respository as well but extra staging area.

Staging - modular control - it comes under local system only..
Ex : Cart to purchase product ..compare purpose


This difference of Git that sets it apart from other VCS, this Staging tree (usually termed as Staging area) is a place where you prepare all the things that you are going to commit. In Git, you don't move things directly from
your working copy to the repository, you have to stage them first, then commit the changes. 
Staging is a cache of files that you want to commit.

![maxresdefault](https://github.com/user-attachments/assets/ffd1c15b-0c87-484d-8299-92a9fcdab259)
















