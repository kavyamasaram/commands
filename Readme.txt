>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>GIT-HUB REPOSITORY<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
                                                              WHAT IF HHTPS:::::

      1.first of all create a directory (mkdir ws)
      2.make the currend directory as ws (cd ws/)
      3.check the version in ubuntu machine of then github repository (git --version)
      4.update and install the git (apt update && apt install git)
      5.create a new repository and then create a ..git file(git init castle)
      6.it will create a repository (ls -la)to check if ..git is created or not
      7.after that make current directory as castle(cd castle/)
      8.after know the present working directory by using the(pwd)\
      9.create a file (touch a.txt)
      10.run git status (git status) it is in workstation
      11.to run in staging are then (git add a.txt)
      12.and to run in local repository (git commit -m "a txt file for project k")
      13.u should create or make a way to push it into main git castle repository from local repositry by using(git remote add origin link of castle                          
        only (httpslink)
      14.after that push that into the castle repository (git push origin master)
      15 it asks the username of github(kavyamasaram)
      16.it also asks the password(Dpjan0201@)
      17.it doesnt accepts passwords do we have to create tokens (github-setting-developersetting-tokenclassics-newclassic token by enabling all the   
      permissions for private key)
      18.again try (git push orogin master)
      19.it asks for the username and password then (usrname=kavyamasaram pp=link that u have copied in the tokems ((we cant see it when we enter that)))
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
                                                            WHAT IF SSH:::::
       1.go to the github then click on code jump to the ssh anc copy the code 
       2. then try to push into castle repositry by using (git remote add ssh-origin "link"
       3.push the code (git push ssh-origin master)
       4.we have to enahle the key of public her using by genreation a key(ssh-keygen)it asks yes/no put yes then click ebter u can find two keys private and         
         public key
       5.copy that public key and cat the key (cat /___________________________) and copy the complete key 
       6.go to git hub setting and gpg key
       7.create a new ssh keys and thenpaste the code there and create a new shh keys
       8.and then push the (code git push ssh-origin master) 
       9 by default it takes as aroot so if u wantto change it then (git config --global --edit)
       10 it opens a pop up contains permissions and then cntl+x to comeback
       11.if u want to edit then u have to convert into vi editor
       12.(export EDITOR=vi)
       13 then start creating a file and do it ..........!

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
                                              to delete from the local rep and main reg and get back them


      1.to delete a file from the registry we use (git reset --hard(ID of the next commit to replace and shift to that commit))
      2.If u want to push the changes to git main registry then (git push origin master --force)
      3.To get back the removed registry then use (git cherry-pick(ID of the file)
      4.to delete only file (git revert(ID of that file)
      5.to remove no of commit use (git reset (id of the next commit to become the master))
      6.to get all the commit u have removed then use( git reset(id of the first commit)
      7 to change the name of origin then (git remote rename origin myntra)
      8.if u want to change the link then (git remote set-url myntra paste url)))............
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
                                                     BRANCHING STATERGY..
1ss 