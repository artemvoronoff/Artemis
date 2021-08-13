Step 1: You have a local version of a repository on your laptop, and to get the latest stable version, you pull from the develop branch.

	a.) Switch to the develop branch:
		git checkout develop 
	
	b.) Pull the latest changes in the develop branch
		git pull

Step 2: When yo ustart working on this demographic feature (that your boss asked), you create a new branch called demographic, and start working on your code in this branch.

	a.) Create and switch to a new branch called demographic from the develop branch
		git checkout -b demographic

	b.) Work on this new feature and commit as you go
		git commit -m 'added gender recomendations'
		git commit -m 'added location specific recommendations'
		git commit -m '...'

Step 3: However, in the middle of your work, you need to work on another feature. So yo commit your changes on this demographic branch, and switch back to the develop branch.

	a.) Commit your changes before switching
		git commit -m 'refactored demographic gender and location recommendations'

	b.) Switch to the develop branch
		git checkout develop

Step 4: From this stable develop branch, you create another branch for a new feature called friends_groups

	a.) Create and switch to a new branch called friend_groups from the develop branch
		git checkout -b friend_groups

Step 5: After you finish your work on the friend_groups branch, you commit your changes, switch back to the development branch, merge it back to the develop branch, and push this to the remote repository's develop branch.

	a.) Commit your changes before switching
		git commit -m 'finalized friend_groups recommendations'

	b.) Switch to the develop branch
		git checkout develop

	c.) Merge the friend_groups brnach into the develop branch
		git merge --no-ff friends_groups

	d.) Push to the remote repository
		git push origin develop

Step 6: Now, you can switch back to the demographic branch to continue your progress on that feature

	a.) Switch to the demographic branch
		git checkout demographic