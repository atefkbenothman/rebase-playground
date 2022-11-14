# rebase-playground

learning how to use git rebase and squash

**steps**

1. fetch remote origin changes  
`git fetch origin/master`

2. merge origin master branch into local master branch  
`git merge origin/master`

3. create new branch  
`git checkout -b feature-1`

4. make changes and commit  
`git commit -m "added part 1"`  
`git commit -m "added part 2"`  

5. fetch from remote origin again (in case there have been new commits by someone else)  
`git fetch upstream`

6. rebase and squash  
`git rebase --interactive origin/master`

7. push your branch to remote origin

8. open pull request
