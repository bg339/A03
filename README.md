## Instructions on Using Webstorm!

# Get all your downloads correct:

```markdown
  Step 1 - Download Webstorm via this link: https://www.jetbrains.com/student/

  Step 2 - Download Git via this link: https://git-scm.com/downloads
  
  Step 3 - Create a Github account via this link: https://github.com/join
  
  Step 4 - Drag the downloaded git version to your desktop
  
  Step 5 - Open webstorm, click control+alt+s, click on version control, then click on git from the dropdown menu. Select the path of the git.exe file which should be on your desktop
  
  Step 6 - After, click on github from the version control drop down menu and link the account you created earlier
  
  Step 7 - Log into git in google chrome or whichever browser and create a repository by clicking the top right + icon and creating a new repository
 
  Step 8 - Create a repository in webstorm. To do so, open webstorm and click "get from vcs". You can either put the url of the repository or you will now see "github" on the left pane. Click on that and your account with all its repositories should be there. Click on the one you want to work on and import it.
  
  Step 9 - Making a file in webstorm. Click on file, new, html, and click on html 5.
  
  Step 10 - Comitting a file. Right click on the file, select git, and then select commit file from that dropdown menu.
  
  Step 11 - To push the file, hit control + k and push the file
  ```
  
# You are done!

# Definitions

```markdown
**Branch** - A "branch" is a line of development. The most recent commit on a branch is referred to as the tip of that branch. The tip of the branch is referenced by a branch head, which moves forward as additional development is done on the branch. A single Git repository can track an arbitrary number of branches, but your working tree is associated with just one of them (the "current" or "checked out" branch), and HEAD points to that branch.

**Clone** - clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.

**Commit** - As a noun: A single point in the Git history; the entire history of a project is represented as a set of interrelated commits. The word "commit" is often used by Git in the same places other revision control systems use the words "revision" or "version". Also used as a short hand for commit object.

As a verb: The action of storing a new snapshot of the project’s state in the Git history, by creating a new commit representing the current state of the index and advancing HEAD to point at the new commit.

**Fetch** - Fetching a branch means to get the branch’s head ref from a remote repository, to find out which objects are missing from the local object database, and to get them, too. See also git-fetch[1].

**GIT** - Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

**Github** - GitHub, Inc. is a provider of Internet hosting for software development and version control using Git.

**Merge** - As a verb: To bring the contents of another branch (possibly from an external repository) into the current branch. In the case where the merged-in branch is from a different repository, this is done by first fetching the remote branch and then merging the result into the current branch. This combination of fetch and merge operations is called a pull. Merging is performed by an automatic process that identifies changes made since the branches diverged, and then applies all those changes together. In cases where changes conflict, manual intervention may be required to complete the merge.

As a noun: unless it is a fast-forward, a successful merge results in the creation of a new commit representing the result of the merge, and having as parents the tips of the merged branches. This commit is referred to as a "merge commit", or sometimes just a "merge".

**Merge Conflict** - A merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits.

**Push** - Pushing a branch means to get the branch’s head ref from a remote repository, find out if it is an ancestor to the branch’s local head ref, and in that case, putting all objects, which are reachable from the local head ref, and which are missing from the remote repository, into the remote object database, and updating the remote head ref. If the remote head is not an ancestor to the local head, the push fails.

**Pull** - Pulling a branch means to fetch it and merge it. See also git-pull[1].

**Remote** - A remote repository in Git, also called a remote, is a Git repository that's hosted on the Internet or another network

**Repository** - A collection of refs together with an object database containing all objects which are reachable from the refs, possibly accompanied by meta data from one or more porcelains. A repository can share an object database with other repositories via alternates mechanism.

```
