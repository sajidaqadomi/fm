## What is the output of git status?

- nothing to commit, working tree clean

--

## Edit the greeting.txt to contain an uppercase greeting

## Add greeting.txt files to staging area and commit

### What is the output of git branch?

- \* feature/uppercase
  main

### What is the output of git log --oneline --graph --all

- \* 52bae41 (HEAD -> feature/uppercase) change to uppercase
- \* cfa66e1 (main) Add content to greeting.txt
- \* 6389de1 Add file greeting.txt


--

### Switch to the master branch

### Use cat to see the contents of the greetings

- hello

--

### Diff the branches

--- a/greeting.txt
+++ b/greeting.txt
@@ -1 +1 @@
-hello
\ No newline at end of file
+HELLO


### Merge the branches

### Use cat to see the contents of the greetings

- HELLO

### Delete the uppercase branch

- PS C:\Projects\fm> git branch -D feature/uppercase
- Deleted branch feature/uppercase (was 52bae41).



Run git status and git log --oneline --graph --all to see what is going on.

HEAD detached at b091377

* 75d7900 (main) D
* e07ee02 C
* 1684e61 B
* b091377 (HEAD) A
* 52bae41 (origin/main) change to uppercase
* cfa66e1 Add content to greeting.txt
* 6389de1 Add file greeting.txt

---
Restore normalcy in this repository by moving to master
Note that this task might seem more confusing if you did not run setup.sh in your terminal.

We want to have a branch called the-beginning that is made from the first commit with message A.
* 75d7900 (HEAD -> the-beginning, main) D
* e07ee02 C
* 1684e61 B
* b091377 A
* 52bae41 (origin/main) change to uppercase
* cfa66e1 Add content to greeting.txt
* 6389de1 Add file greeting.txt