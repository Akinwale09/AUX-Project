## AUX PROJECT 1: SHELL SCRIPTING
### How to automate some work using Shell Scripts
### In this project, I will onboard 16 new Linux users onto a server. I will Create a shell script that reads a csv file that contains the first name of the users to be onboarded. 

## Creating a Shell Script

`vi onboard.sh`
![Shell Script](images/shellscript.png)

### The code in onboarding users Linux Shell was added and saved

### I make a directory 'Shell' and cd into the diectory

`mkdir Shell`
`cd shell`

![Make Dir](images/makedir.png)

### I move my onboading file into the shell directory

![Move](images/move.png)

### ls into the shell derectory to confirm my onboarding file

`ls`
![LS](images/lstoshell.png)

### I create a file for the public key 

`touch id_rsa.pub`
![touch](images/pub.png)

### I open the file using your favorite editor and paste in the public key

`vi id_rsa.pub`

![edit](images/editpubkey.png)

### I create a file for your private key

`touch id_rsa`
`vi id_rsa`

![rsa](images/rsa.png)

### CHMOD onbaord file

![CHMOD](images/chmodonboard.png)
### create developers group

![developer](images/adddeveloper.png)

#### all the 16 users added to developers group

![users](images/usersadded.png)

### all the 16 developer added to developer group

![group](images/devconfimed.png)








