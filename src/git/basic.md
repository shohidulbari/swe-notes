-  Checkout to a remote branch
	```bash
	git  fetch  {{remote  name}}  {{branch  name}} && git  checkout  -t  {{remote  name}}/{{branch  name}}
	```
- Add all changes in latest commit without modifying commit message
	```bash
	git commit --all --amend --no-edit
	```
- Rebasing with interactive shell
    ```bash
    git rebase -i {{base branch}}
    ```

- Show all the stashes
	```bash
	git stash list
	```

- Stash with a message
	```bash
	git stash save "This is a message"
	```