$ mkdir VCS_Lab2
$ cd VCS_Lab2
$ git init
$ git remote add origin git@github.com:Abdullah-MLE/ITI_VCS_Course_Lab2.git
$ touch file1
$ git add .
$ git commit -m "first_commit"

$ git switch -c dev
$ git add .
$ git commit -m "2'nd_commit_test"

$ git switch -c test
$ git add .
$ git commit -m "3'rd_commit_dev"

$ git push origin dev
$ git push origin test

$ git switch dev
$ git merge test
$ git switch main
$ git merge dev
$ git push

- Tell me how to remove them locally and remotely?
$ git branch -d test
$ git branch -d dev

$ git push origin --delete test
$ git push origin --delete dev

- Tell me how to checkout another branch without commit changes?
$ git stash
$ git stash pop

$ git tag -a "v1.7" -m "version 1"
$ git push origin tag v1.7

- list tags?
$ git tag -l

$ git tag -d v1.7
$ git push -d origin v1.7

- add image in the md
- ![alt text](pic.png "Title")



![alt text](pic.png "Title")

