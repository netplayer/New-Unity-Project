For Version Control:
---------------------
1.download https://desktop.github.com/ and install
2. Run and setup a new account (you can login on github.com with same credentials)
3. Watch the tutorial or skip it
4. Open Unity and do the following:
   -Enable Visible Meta files in Edit->Project Settings->Editor
   -Switch to Force Text in Editor → Project Settings → Editor → Asset Serialization Mode
5. Save unity project and close unity
6. Go to github client (the program not the site) and on the left menu chose add and navigate to the project folder and select it
7. You will be asked to create a new repository, click it yes and go on
8. After the repository is created you can see two selections on top  of the program interface, Changes and History Click history and click publish.
9. Go to the github site to check project is also created there.
10. Go to Changes tab you will see a list of changed files (in fact are the project files that have to be added to the repo for the first time). Put a title as required and click commit. It will take some time untill this ends (too many project files) and when this commit is visible in History tab publish this also (also will take much time) 
11. Check files on github site.

The logic is that whenever a file is added/changed in the project they will appear in changes tab and you will commit them.
If for any reason local repo is deleted you have them inline and you can also change what version uploaded you want to recover either through github desktop client or directly from github site.

You can see my unity projet's repo at https://github.com/netplayer/New-Unity-Project. Actually you can fork a branch through github desktop or just download all the files zipped from the site. To fork it, first fork it on the site, so it will appear in your repos and then with Github desktop  on the left menu clicking Clone you get it on your pc as a github clone which you can update later same way.

We can work on same repo if the you make a pull request to the original owner so commits will be made also on original files (owner will be able to accept or reject commits after reviewing them).
You can find this document on the above repo as README.txt  


For packaging Unity project:
------------------------------

To make an executable use the File->Build and Run . You will see you can build for various platforms.