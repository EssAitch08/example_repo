
- git clone <SSH path>

- git config --global user.email "hoelzlstefan08@gmail.com"
- gitgit config --global user.name "stefanhoelzl"

-  git branch --unset-upstream --> fix broken upstream (e.g. URL changed, etc..)


- git status

- git diff >file<

- git log
- git lg
	(--> put following into C:\Users\XY\.gitconfig)
			[alias]
				lg = log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'
	References: https://codingforeverybody.com/snippets/git-lg and https://www.onwebsecurity.com/configuration/git-on-windows-location-of-global-configuration-file.html

- git add >file<  --> staging for commit
- git commit -m "the commit message"
- git push origin master --> push to origin/master

- git checkout commit hash --> set HEAD to some point


- git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'