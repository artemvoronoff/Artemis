Scenario #2

Step 1: You check your commit history, seeing messages about the changes you made and how well the code performed.

	a.) View the log history
		git log

Step 2: The model at this commit seemed to score the highest, so you decide to take a look

	a.) Check out a commit
		git checkout "afsdf2342sdcvc324rvc23 (random code)"

After inspecting your code, you realize what modifications made it perform well, and use those for your model.

Step 3: Now, you're confident merging your changes back into the development branch and pushing the updated recommendation engine.

	a.) Switch to the develop branch
		git checkout develop

	b.) Merge the friend_groups branch into the develop branch
		git merge --no-ff friend_groups

	c.) Push your changes to the remote repository
		git push origin develop

		