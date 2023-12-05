# gittraining

> This is a step by step list of git command to create and to update repository based on several cases.


## TO CREATE A NEW REPOSITORY ON THE COMMAND LINE

> List of git commands to create a new repository from your git terminal:

-   echo "# gittraining" >> README.md          <===  Create a README.md file with a content   (locally)
-   git init                                   <===  Create a new Git repository (locally)
-   git add README.md          		     <===  Add a change in the working directory to the staging area  (locally)
-   git commit -m "first commit"               <===  Capture a snapshot of the project's currently staged changes  (locally)
-   git branch -M main         		     <===  Force to rename the current branch to "main"   (locally)
-   git remote add origin git@github.com:cvidaillac/gittraining.git          <===  Add a new remote repository defined with origin (locally)
-   git push -u origin main         	     <===  Push local code to the master branch of remote repository defined with origin (sent to Github)
  
  
