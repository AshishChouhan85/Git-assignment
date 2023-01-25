# Git-assignment

The default branch is Production branch.
Command used:
git branch -m Production

A txt file named test.txt was created in this branch and the change was commited and pushed to github.

Two other branches named HotFix and Integration were created and pushed to github.
Command used:
git branch HotFix
git branch Integration

Two branches named Feature1 and Feature2 were created from Integration branch and pushed to github.
Command used:
git branch Feature1 Integration
git branch Feature2 Integration

A file named feature2.txt was added in Feature2 branch.
This changed was commited and pushed to github.
A PR was created and merged with Integration.
Then Feature2 branch was deleted.

A file named feature1.txt was added in Feature1 branch.
git pull was used to pull changes made in Integration branch.
Now Feature1 branch was rebased with Integration branch and this change was pushed to github.
Command used:
git rebase Feature1 Integration

PR were created to merge Hotfix and Production branch with Integration branch.
A file named Feature1_2.txt was created in Feature1 branch and this change was commited and pushed to github.
Using a PR this change was merged with Integration, HotFix and Production branch.
Now, Feature1 branch was deleted.

All the branches were pulled in the local repo to keep them upto date.
Now, a file named Hotfix_feature.txt was added in HotFix branch.
This change was commited and pushed to github.
Now using PR the hotfix branch was merged with Integration and Production branch.


