Hello!!!
This is a test.
Lets see how far I have come.

Some unix commands that are usefull (used in PS):
mkdir name  -> create a folder in the current map
mkdir C:\lkjsdf\KSJDf\KSJDF name   -> create a folder in a subdirectory/map you are not in yet

ls  -> list the folders within the directory you are in
cd name map in the list (example alfabet)  -> change to another directory

cd ..  -> goes to the previous directory

rm name -> remove a file with that name
rm c:\SDKJF\JHXf\DS name ->remove file with a name from a directory you are not currently in


I need to chance some stuff and see if it works.
So lets see
It didnt work in PS for some reason but it does in the desktop UI.
But I want it to work in PS too....
So attempt 2 lets go!

So the issue is that the challenge with steps is incomplete.

1. git status
2. git add name
3. git stage name
4. git commit -m readme.txt


Going global whoohoo
*\o/*
How you do it (unix code):
1. git config --global user.username absdc
Check to see if it works:
git config --global user.username  -> shoud say absdc now


oke so we put everything online:
git remote add origin URL

In my case this meant I also had all the files from this folder online already.
After changing the document and comitting it offline you can push it towards online.
1st do steps 1-4 (git status, git add name, git stage name, git commit -m name)
then use: 
git push origin master

So now I know how to get a copy of files from the server on my own pc.
Thats called a clone..
Code: git clone URL  -> this will put a folder and all files from that URL into the directory you are in.
So if you dont want it in your "hello world" folder change directory to the above directory (with cd ..)
Then use the command line for the clone.

next to your clone you want a link to the original file on the server.
You get this by going to the serveradres from patchwork and using the commandline: 
git remote add upstream URL

the command: git remote -v   -> is used to see what URL's are linked to a directory