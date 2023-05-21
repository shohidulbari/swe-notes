-  Checkout to a remote branch
	```bash
	git  fetch  {{remote  name}}  {{branch  name}} && git  checkout  -t  {{remote  name}}/{{branch  name}}
	```
- Add all changes in latest commit without modifying commit message
	```bash
	git commit --all --amend --no-edit
	```