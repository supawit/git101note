# Introduce Git
  Git is version control

# Github Account
  Go to https://github.com/ and SignUp.

  1.Create Github public key 

	  commmand : $ssh-keygen -C Author 

	  Keycode will be generate in id_rsa.pub on .ssh folder 

	  e.g. C:\Users\Mc\.ssh\id_rsa.pub 


  2. Sync to Github

  	 Go to Github site on menu Setting->SSH and GPG keys

  	 Click New SSH Key and paste CODE from id_ras.pub

  	 And Sync to Git by command : $ssh -T git@github.com 

  3. PUSH

  	 Create a new repository.

  	 Set add remote origin URL that created by command : git remote add origin git@github.com:userxx/hello.git

  	 Push by command : git push / or git push origin master

  4. PULL

   	 by command : git pull URL

# git command
## revert
like undo revert to previos commit then create new commit

# Branch
  - git branch : Command to view all branch in the project.
  - git branch [branchname] [basebranchname]: Command to crete new branch by name [branchname] from [basebranchname]. 

# ADD
git-add - Add file contents to the index

Command 
- git add <filename.type> 
- git add . (all file)

# COMMIT
git-commit - Record changes to the repository

# Command
- git commit -m 'comment'
- git commit -am 'comment' (short code : add & commit)
