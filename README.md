ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465 (main)

$ echo "Today is finals!" > MyTestFolder/finalExam.txt



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465 (main)

$ git add MyTestFolder/finalExam.txt

warning: in the working copy of 'MyTestFolder/finalExam.txt', LF will be replaced by CRLF the next time Git touches it



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465 (main)

$ git status

On branch main

Your branch is ahead of 'origin/main' by 2 commits.

  (use "git push" to publish your local commits)



Changes to be committed:

  (use "git restore --staged <file>..." to unstage)

        modified:   MyTestFolder/finalExam.txt





ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465 (main)

$ cd MyTestFolder



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465/MyTestFolder (main)

$ ls

finalExam.txt



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465/MyTestFolder (main)

$ nano finalExam.txt



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465/MyTestFolder (main)

$ git status

On branch main

Your branch is ahead of 'origin/main' by 2 commits.

  (use "git push" to publish your local commits)



Changes to be committed:

  (use "git restore --staged <file>..." to unstage)

        modified:   finalExam.txt



Changes not staged for commit:

  (use "git add <file>..." to update what will be committed)

  (use "git restore <file>..." to discard changes in working directory)

        modified:   finalExam.txt





ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465/MyTestFolder (main)

$ git add MyTestFolder/finalExam.txt

warning: could not open directory 'MyTestFolder/MyTestFolder/': No such file or directory

fatal: pathspec 'MyTestFolder/finalExam.txt' did not match any files



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465/MyTestFolder (main)

$ cd ..



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465 (main)

$ git add MyTestFolder/finalExam.txt

warning: in the working copy of 'MyTestFolder/finalExam.txt', LF will be replaced by CRLF the next time Git touches it



ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465 (main)

$ git status

On branch main

Your branch is ahead of 'origin/main' by 2 commits.

  (use "git push" to publish your local commits)



Changes to be committed:

  (use "git restore --staged <file>..." to unstage)

        modified:   MyTestFolder/finalExam.txt





ogunb@KvngKiishi MINGW64 ~/Documents/COSC 465/cosc465 (main)
