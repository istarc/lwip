lwip
====

Unofficial lwIP Clone git://git.savannah.nongnu.org/lwip.git

Created by:

	# Clone Empty Repository (/w .gitignore and README.md)
	git clone https://github.com/istarc/lwip.git
	# Add Upstream Repository
	git remote add upstream git://git.savannah.nongnu.org/lwip.git
	# Fetch from Upstream
	git fetch upstream
	git merge upstream/master # Merge master with the upstream
	git push --all origin # Push each branch to origin
	git push --tags origin # Push each tag to origin

Clone (no warranties):

    git clone https://github.com/istarc/lwip.git

Update:

    git rebase upstream/master

Checkout a tag:

    git tag -l
    git checkout STABLE-1_4_1
