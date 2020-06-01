Managing Remotes in Git

once you create a repo and clone it, it basically maintains a pointer to the source. This pointer is an example of a remote in Git. A remote is a pointer to another copy of the same repository. When you clone a repository, a pointer (origin) is automatically created which points to the source.

!. You can check a list of remotes in a repository by running the following command:
git remote -v

2. To add a remote, you can use the git remote add command:

 git remote add remote_name remote_address

3.You can remove a remote using the git remote remove command:

 git remote remove remote_name
 
4. If you’d like to change the address of a remote, you can use the set-url command:

git remote set-url remote_name new_remote_address