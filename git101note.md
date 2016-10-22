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