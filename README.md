# tryi
using ls with '-a' gives all file list in directory
to clone repo first create one then click on code then copy https then come to terminal any type git clon and paste copied link
after modifying file first add then commit 
M symbol in file explorer mean modify in file 
after adding file files are staged it mean they are readdy for commits 
git add <-file name> to add a file adds new or changed file into staging area
if you have lot of file in which you changed something you can use git add . (literally a dot)
git commit - it is record of change 
git commit -m "feature you changed or fixed bug"
after doing commit you type git status it will display----
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

this simply means that on local machine we are one commit ahead as compared to our github repo

in changes ko system me to krdiya per inko github pe dikhane ke liye humko dusri command type krni hogi
git push originn main
push command se dhakka deke local repo ke content ko remote repo me fekte hai


INIT command 
init-used to create a new git repo

local machine pe hi repo bananne ke liye hai ye method
pehle iss folder se bahar aao cd.. krke
fir uske baad mkdir localrepo folder banao
fir cd localrepo me jaao  ls -a se check krkste hai ki yeh abhi repo hai ya nahi agr ls-a krne se . .. or .git folder dikaye to repo hai agr nahi to nahi hai 

fir git init dabao  -- Initialized empty Git repository in --- ye likha hua aayega or in ke baad file destination likhi hoti hai privacy ki wajah se yaha e hide kardi 
U matlab untracked hai

ab hamne files banadi add or commit  bhi krli ab isko repo me dalne ke liye 
github me jake new repo banao readme.md to uncheck krdenge kyuki usko add kiya toh pehle iss new repo ko system me lana padega faltu paccchda kon lera 
ab git remote add origin<-link>  ye command type krenge 
ye remote humri remote repo hai or naam iska origin rkhre hai
ab origin set hogaya, kya set hua vo check krne ke liye git remote -v us krskte hai
git branch  --- humko check krke bataegi hum konsi branch me hai
git branch -M main -- used to rename a branch in github
