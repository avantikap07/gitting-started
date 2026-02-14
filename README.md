# Gitting Started With GIT 

## Initials

**test for git** 
```gh --version``` 
to check the version of your github ! if something appears then ignore n move on lololol , else

```winget install --id GitHub.cli``` 
this is for windows (the WINget) this shud install the cli if you do not have it in your system 

```gh auth login``` 
sets your login up!

## Making your first repository!!

**Making your file** 
```mkdir <foldername>```
creates your folder : in essense an empty folder locally on your device!
 
**Initializing the created file!**
```git init -b main```
Yep once this command , you basically have your own repository rn!
the ```-b main``` jus ensures that the its in the main branch 
you should essentially see the entire thing turn greeenn (given u have the extension , wht abt otherss?)

**Creating files and adding them to the "parcel"** 
A reallyy easyy process , stick with me through this!

```touch firstcomit.jsx```
Touch simply creates a jsx file (react)

```echo "#My first Project" > README.md```
Creates your readme file with a couple of text inside it!

```git add .```
Okay so , what this essentially does is , say your sending a parcel to your github okayy? with this command your essentially putting the created files *firstcomit.jsx* and *Myreadme.md* into a box - think it that way... now that they r inside a box ,  you gotto do is seal and to send the parcel right? how would you do that? really simple , stick with me!

```git commit -m "Week 1 : My first commit <name>"```
you just sealed the box tight and added a message to it , so that when it reaches github , everyone who reads to access it knows what it is! 

**Creating your repo and pushing it to the website** 
```gh repo create my-first-repo --public --source=. --remote=origin --push```
sends our package to github successfully!!! ```--public``` essesntially sets the repo as a public repo!
```--source=.``` basically selects the entire contents of the folder "." the dot basically does that 
```--remote origin --push``` pushes it into your repo (origin here being the petname of your url link)

**confirming your repo creating!**
```gh repo list``` 
this command shows you all the repo's that you have created!



## Git Cloning!

```git clone <link>```  
This command create a local copy of the repo into your system - making it easier for you to edit files locally! 
followed by this a 
```code .``` 
opens the very same file in your VS Code
