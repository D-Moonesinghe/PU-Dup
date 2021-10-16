### Remote Updates:
## Wow.MD
Wow. I didn't know I could do this.  But it all worked.

### What I Did to create this repo

  1. I create a local repo.  Added some files to it. 
  1. I created a blank repo on github.  (Without a single file.)
  1. Copied the URL from the Github blank repo and setup the local remote.
  1. Then I pushed the local repo to GitHub.
  1. It successfull pushed upsteam.
  1. Now I am creating this file on github and intend to pull it from local.

  Lets see if I can pull this down.  But first create a pull request for Wow.md.
  I guess I don't need a pull request because this was created in the main branch.

  ### Local Update

  1. First it failed to fetch or pull.  Because it was looking to bring down a branch master.  Only then did I notice that my local branch was still called master; while the new repo I created on GitHut had its default as 'main'.
  1. I renamed the local master to main very easily with Kracken.  Then I tried a pulled it failed because it was looking for a upstream master.  I wen to .git/refs/remotes/origin and renamed the branch to main.  This allowed me to get my push/pull working.
  
