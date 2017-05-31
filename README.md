# use your own repo
 mkdir ~/bin 
 export PATH=~/bin:$PATH 
 cp -rf repo/repo ~/bin
 chmod a+x ~/bin/repo

# change repo to your own repo
		REPO_URL = 'https://gerrit.googlesource.com/git-repo'
	to	REPO_URL = 'https://github.com/zSkull/repo.git/repo'	
# init repo
 repo init -u manifesturl(https://github.com/zSkull/manifest.git)
 repo sync


