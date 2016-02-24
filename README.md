Starting a new project:

1) Clone a copy of the News Apps Template from Chris' Git page
2) Rename the repository locally

$ git clone [repository url] new-folder-name



Save to YOUR repository:

1) Add all untracked files to the repository
$ git add . 
OR 
$ git add -A

2) Create a new repo on YOUR Git page

3) Removed the original ORIGIN (which links to Chris' Git page)
Navigate to folder in terminal, then do 
$ git remote show origin
$ git remote rm origin

4) Add YOUR origin to the repository
$ git remote add origin [url for your new repo with .git at end]

5) Commit your changes
$ git commit -am "add a comment"

6) Push to new repository
$ git push origin master