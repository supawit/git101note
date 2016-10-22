# Github Account
  Go to https://github.com/ and SignUp.
<<<<<<< HEAD

  1.Create Github public key 

	  commmand : $ssh-keygen -C Author 

	  Keycode will be generate in id_rsa.pub on .ssh folder 

	  e.g. C:\Users\Mc\.ssh\id_rsa.pub 


  2. Sync to Github

  	 Go to Github site on menu Setting->SSH and GPG keys

  	 Click New SSH Key and paste CODE from id_ras.pub

  	 And Sync to Git by command : $ssh -T git@github.com 
=======
  1.Create public 

# git command
## revert
like undo revert to previos commit then create new commit

# Branch
  - git branch : Command to view all branch in the project.
  - git branch [branchname] [basebranchname]: Command to crete new branch by name [branchname] from [basebranchname]. 

# ADD
>This command updates the index using the current content found in the working tree, to prepare the content staged for the next commit. It typically adds the current content of existing paths as a whole, but with some options it can also be used to add content with only part of the changes made to the working tree files applied, or remove paths that do not exist in the working tree anymore.

Command 
* git add <filename.type> 
* git add . (all file)
>>>>>>> 87ce328109655de52cec7ecc2aaa5629e05971fe
