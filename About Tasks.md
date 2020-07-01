# Github-Series #
## Day-1 ##
### About Git and GitHub ###
Git : -Installed locally.
      -Open source tool to merge source code.
      -VCS that's lets you manage and keep track of your source code history.
GitHub : - Hosted in cloud.
         - Online service to which developers who use Git can connect and upload or download resources.
         - Cloud based hosting service that lets you mange Git versions.
        
### About Version Control System ###
- It tracks all the changes made to your code and who makes them.
-One can always review the detailed change log that has all the information.

### Some Platform similar to Github ###
1- GitLAB
2. BitBucket
3. LaunchPad

## Day-2 ##
### Git Workflow ###
Four fundamentals of Git workflow:
1. Workspace - which is your lead directory.
2. Index - also called stage
3. Local Repository - HEAD
4. Remote Repository

### Different stages of Git project ###
1. Untracked - file exists,but not pushed to Git VCS.
2. Staged - file added to git vcs but changes have not been commited.
3. Committed - Change has been committed.

### Use of Git diff ###
Git diff is used to track difference between changes made on the file. It only shows the difference between your working copy and repository.

Link to GitHub repository :
https://github.com/PriyanshiChamoli/git_series.git


## Day-3 ##
### Forking and Cloning ###
-Working on someone else project or using there project as starting pointof your own is known as forking.
- Forking can only copy your project but project still remain on GitHub so to be able to work on the project you will need to clone it to your computer this process is called cloning.

### Branching ###
Branching is used to isolate development work without affecting other branches in repository.
Branches serve as an abstraction for edit,stage, commit process.

### PR - Pull Request ###
It let's you tell others about changes you have pushed to a branch in a repository on github.
Once a PR is opened you can discuss and review changes and commit before your changes are merged into base branch.

PR Links:
https://github.com/codewayy/github_series/pull/74
https://github.com/PriyanshiChamoli/git_seres/pull/1

## Day-4 ##
### Merging ###
It is Git's way of putting a forked history back together again.
The Git merge command lets you take independent lines of development created by git branch and integrate them into a single branch.

### Merge Conflict ##
A merge conflict is an event occured  when there are conflicting changes on the same lines, so git doesn't know which code to keep and which code to discard so it become unable to automatically resolve differences in code between two commits . So this problem needs to be resolved manually.

### Creating an Issue ###
Issues can be used to keep track of bugs, enhancements, or other requests.
### Steps ###
1. On GitHub Enterprise, navigate to the main page of the repository.
2. Under your repository name, click  Issues.
3. Click New issue.
4. If there are multiple issue types, click Get started next to the type of issue you'd like to open.
5. Type a title and description for your issue.
6. If you're a project maintainer, you can assign the issue to someone, add it to a project board, associate it with a milestone, or apply a label.
7. When you're finished, click Submit new issue.

PR link: http://github.com/PriyanshiChamoli/github_series-1/pull/1
Issue link:
https://github.com/codewayy/github_series-1/issues/103
