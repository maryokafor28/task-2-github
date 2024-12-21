# task-2-github

WHAT IS VERSION CONTROL?
Version control also known as source control is the practice of tracking and managing changes to file.

EXPLAIN DIFFERENCE BETWEEN GIT AND GIT HUB
Git is used for tracking code changes and also for coding collaboration

Git hub is a code hosting platform for veersion control and collaboration.it lets you and others work together on projects from anywhere.

LIST 3 OTHER GITHUB ALTERNATIVES

1. Gitlab
2. Bit bucket
3. Aws cloud formation

EXPLAIN THE DIFFERENCE BETWEEN GIT FETCH AND GIT PULL
GIT PULL:
Git pull copies changes from a remote repository directly into your working directory. it is faster as you are performing multiple actions in one.

GIT FETCH:
Git fetch command only copies changes into your local git repo. it also pulls in all the commits for ypur remote but doesnt make any changes to your loval files.

EXPLAIN IN SIMPLE TERMS GIT REBASE AND THE COMMAND FOR IT
A git rebase chnges the base of the developers branch from one commit to another, so it looks like they have created their branch from a different commit

IT'S COMMAND IS;
git rebase branch (rebase the current branch onto another)
git rebase -i commit (allows to modify commit)
git fetch origin
git rebase origin branch

EXPLAIN IN SIMPLE TERMS GIT CHERRY-PICK AND THE COMMAND FOR IT.
Git-cherry pick: Apply the changes introduced by some existing commits. Git-cherry pick is the act of picking a command from a branch and applying it to another.

IT'S COMMAND IS;
Git vherry-pick commitsha
git checkout main
git cherry-pick "f" (assuming we wanted to use commit "f" on main)
