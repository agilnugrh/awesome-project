$ vim README.md
$ cat README.md
# My Awesome Project

$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md

nothing added to commit but untracked files present (use "git add" to track)
$ git add -A
$ git commit -m "Add: README.md"
[main 2ab2e28] Add: README.md
 1 file changed, 2 insertions(+)
 create mode 100644 README.md
$ git push origin main
Username for 'https://github.com': oldstager
Password for 'https://oldstager@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/oldstager/awesome-project
   8dd68d4..2ab2e28  main -> main
$
