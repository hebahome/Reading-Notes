
# Git Tutorial: A Comprehensive Guid 
![Git](https://blog.udemy.com/wp-content/uploads/2015/08/banner_GIT.jpg)

[Git](https://blog.udemy.com/git-tutorial-a-comprehensive-guide)

##  1- Version Control
### Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

## 2- Local Version Control
### Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.

##  3- Centralized Version Control
### This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.
  
## 4- Distributed Version Control

### In the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.


## So, what is Git?
### - Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

### - Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

### - Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

### - States

Files in Git can reside in three main states: committed, modified and staged.

### - Committed

Data is securely stored in a local database

### - Modified

File has been changed but not committed to the database
