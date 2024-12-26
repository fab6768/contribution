# contribution
My public Contribution if it helps... :)


# Links

| Information | Link |
| --- | --- |
| Git_portable | https://github.com/git-for-windows/git/releases/download/v2.47.0.windows.1/PortableGit-2.47.0-64-bit.7z.exe |

--------------------

# Git_Bat

<details>

<summary>CMD</summary>

### Install Git Portable:

```cmd
   mkdir C:\Adminsys
   cd C:\Adminsys
   git clone AAA
```

</details>

--------------------

# Git_CMDs

<details>

<summary>GIT</summary>

### Git Configuration:
```
git config --global user.name "$Name $Surname"
git config --global $mail
```

### Git_Commands:
```
branch_main="main"
branch_name=""
branch_comment=""

git checkout $branch_main
git checkout -b "$branch_name"
git status

## New Files / do Stuff....
git add $file1
git add *

git commit -m "$branch_comment"
git push --set-upstream origin "$branch_name"
git checkout $branch_main

## Clean Local
a_repos=`(git branch -l | egrep -v "$branch_main")`
git checkout $branch_main; for repo in $a_repos; do git branch -d "$repo"; done

```
### Git Fix:
```
git config --global --add safe.directory $path
```

</details>

--------------------


