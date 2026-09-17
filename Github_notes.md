Here we write the notes for the Git and Github
Git is a version control system. To explain in laymen terms, it is like storage for code. And Developers can contribute ti a single codebase. Codebase Reviews Merging and Many can be done.
Git should be installed in the system. to check that type the command in the terminal
git version git version 2.50.1 (Apple Git-155)
When git is installed it gives out the version.
Then open the folder you need to install git in and to have the git track the code an dstore the code and code changes.
First check whether already git installed in any folder by entering the command in the terminal.
git status
fatal: not a git repository (or any parent up to mount point /Volumes)
Initialise a git repositroy by entering the command git init
This initialises the git into the folder and it has teh track of the folder and the code changes.
Initialized empty Git repository resonse will be this.
After Initialising you can see at the end of the each file U symbol comes which means untracked.
So that means git is not tracking the particular files and the folder.
After that git add . adds all the folders and files present in the folder. or you can add a particular file as well by typing git add filename
And whenever you are changing anything in the file or the folder you can see M at the end of the file which indicates Modified. Git tracks everything and every change.
To store the code in the git we should write a command such as git commit -m "Message" this stores the code in the git.
To see the tree of the git version control like details when is the commit and all
git log --all --graph is the command
It gives commit hash key usually the code for directly seeing the commit at any point of time because if i belive many changes happen and whenever any website or product gets a bug or a problem to role out to the previous version they need the exact commit or previous build so that can roll back.
(HEAD -> main) this is the displayed output So Head is always like at present Where is the code and it points to one branch that is main.
You can create branches with the command git branch branchname.
This creates the branch with a branch name.
Then to switch to the new branch you can enter a command git switch branchname.
It switches to the new Branch.
You can verify by typing the command git log --all --graph
Now as you switch to any branch and start changing the code there when you are in that particular branch. Then the code changes and everything is recorded and tracked in that particular branch.
And again you add the file there at present branch and then commit the files.
When you shift to the main branch again like git switch main. You dont see the changes done in the branch.
This is because when a single big project is being done many features are done in many branches and when testing everyhting is doen then it is pushed to the main branch.
So now When its time to merge the contents from the branch to the main root.
What do we do
First move the HEAD to the main root
git switch main, it switches to the main root. Then whatever branch you want to merge to the current main branch you just type git merge branchname this comannd merges the branch to the amin branch.
Beauty if git is i was in the branch and i made a file change. and without commting that code to the code i thought to switch the head to the main root. git warned me see there are files or the code you changed when you want to switch to the main root whatever you worked while you were in thsi branch might be lost, so please commit the code and then switch.
git switch hashkey also switches the branch and the branch stays the same eventhough you merged the code from the branch. While committing the code always add the message otherwise git warns for that aswell.
type q for exiting the tree mode
Here we typed type q for exiting tree
Okay now we understood how it looks. We tried to see the changes in the same line of 37. In main root we had typed something and when we created another branch and then typed something else in line 37 then when we go to the main root and try to merge the branch file to the main root it asked for whether what to do take the incoming change or the current change or tale both and keep first one top or bottom so we have veriety of changes being done by the git which is helpful and we know how and what to accept all the things.
Here is the image of Merge conflict
