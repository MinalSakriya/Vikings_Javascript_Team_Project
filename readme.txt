Hi there troops,

I have added the corrct branches now so they should be working ok.

When you are in your terminal please type 'git pull origin develop'.

Then create a new branch. (eg: 'gco -b feature/add-get')

From here you are working from within your own branch.


When it comes time to commit then you can just type the usual stuff to commit eg: 'gaa - to add all files to staging area, gcmsg "message" to commit with a detailed message'

Then when it comes to pushing the files make sure the red font in your terminal says the name of tyour branch and then type 'git push origin <branchname>'

Go to the github repo and check that changes have been made and the correct files are there in your own branch.

Then create a new pull request and request that the other two people need to see it. This can be done on the right hand side of the screen.

Also make sure that the base of the merge is the develop branch. This will be default set to master, so make sure you change it.

As long as you set the request that the other two people need to review it then they will get an email and will be able to go and check it. Once the pull request is made then send a message in the slack groupchat. Once everyone has had a chance to check it then the pull request can be merged.

After your own merge request has been approved, delete your branch and make a new pull request for the develop branch so that your files are up to date.

If you are working on something during this merge then wait until your work is finished and then make your own merge request. After this is approved you will need to pull down the most recent version of develop.
