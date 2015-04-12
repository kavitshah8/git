Levels of configurations:
1. System ( git config --system )
2. User ( git config --global )
3. Project ( git config )

For example:
	git config --global user.name "Kavit Shah"
	git config --global email "foo@bar.com"
	[git config --global core.editor "subl -n -w"](https://help.github.com/articles/associating-text-editors-with-git/)
	git config --global color.ui true
	git config --list 