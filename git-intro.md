# Git - intro
Git  is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows 
< thousands of parallel branches running on different systems 
## So, what is Git inytro ?
1. Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

2. Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

3. Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

4. Staged
Flagged a file’s changed version to be committed in the next snapshot

 ![Flagged a file’s changed version to be committed in the next snapshot
](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

## Graphical Clients
Git includes inherent Graphical User Interface (GUI) tools. However, users can also utilize third-party tools created for particular platforms.

## Workflow
 ![work folw](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

 ## Saving Changes
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

## The Life Cycle of File Status

![The Life Cycle of File Status
](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

## Tracking and Staging a New File

Track one file only by using the following format:

git add filename

## Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message:

## Pushing Changes
Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.



