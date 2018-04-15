# repo

Repo is a tool built on top of Git.  Repo helps manage many Git repositories,
does the uploads to revision control systems, and automates parts of the
development workflow.  Repo is not meant to replace Git, only to make it
easier to work with Git.  The repo command is an executable Python script
that you can put anywhere in your path.

* Homepage: https://code.google.com/p/git-repo/
* Bug reports: https://code.google.com/p/git-repo/issues/
* Source: https://code.google.com/p/git-repo/
* Overview: https://source.android.com/source/developing.html
* Docs: https://source.android.com/source/using-repo.html
* [Submitting patches](./SUBMITTING_PATCHES.md)

# over the auto update
	mkdir $workdir
	mkdir $workdir/.repo
	cd $workdir/.repo
	git clone https://github.com/zSkull/repo.git
	cd $workdir
	repo init -u https://github.com/zSkull/manifest.git

# you may need to set your mail and name
	git config --global user.mail "***"
	git config --global user.name "***"

