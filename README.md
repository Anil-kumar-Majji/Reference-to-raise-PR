# Reference-to-raise-PR
In following, I documented about the raising PR and methods to follow while doing code modifications in local repo.
## I. Following steps are while doing code solving and push into remote repo:
##### 1. Everytime create a local branch in which the modification has to be apply with command 
    - < git checkout -b "New branchName">
##### 2. Reset the new branch with the code from upstream/develop
     - <git reset --hard upstream/(Branch-Name)>
##### 3. Now do the modifications in file whereever required
##### 4. Later use commands to add the files in stage
    - <git add .>                         //If want to add high number of files to stage in git
    - <git add "File relative path">      //If want to add one file
#### 5. If we want to unstage a particular file
    - <git restore --staged File-Path>
##### 6. Do commit  with a respective message
    - <git commit -m "Message">
##### 7. Now push the code into origin repository
    - <git push origin (Branch-Name)>

## II. Following steps are to raise PR:
##### 1. Select the respective branch in remote repo.Choose the pull-request option to select raise new PR button.
##### 2. Now select MOSIP/inji and develop branch as "base-repo". My repo and new branch as "head-repo".
##### 3. Check the comparision in below. Put comments if any required. Click on pull-request.
##### 4. Share the PR files changed link to further code-review before merge.
