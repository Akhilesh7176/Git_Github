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
