Levels of configurations:

1. `git config --system` (System level)
2. `git config --global` (User level)
3. `git config`(Project level)

For example user level configurations are shown below:
```
git config --global user.name "Kavit Shah"
git config --global email "foo@bar.com"
git config --global color.ui true
```
[git config --global core.editor "subl -n -w"](https://help.github.com/articles/associating-text-editors-with-git/)

`git config --list`
