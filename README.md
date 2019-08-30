# solid-guacamole
Some Bash command repo for me to do keep saking. I plan to keep three sections based on what I work on

| Command        | Purpose      | 
   | ------------- |:-------------:|
   |Markdown cheat sheet link    | https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet |
   
   
 
  ### Docker images commands
  
 | Command        | Purpose      | 
   | ------------- |:-------------:|
   |Inspect docker container    | docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' container_name_or_id | 
   |Removing old Docker containers    | docker rm $(docker ps -q -f status=exited) |
   |Running an image    | docker run -it <image-name>  |
   
   ### Aws commands for CLI
   
   |Command|Explaination|
   | ------------- |:-------------:|
   |aws configure |To set default profile. Best practice don't set one|
   |aws sts get-caller-identity --profile aws-profile-user2 |Command to do a AWS cli task by setting the --profile tag|
   |source awsswitch/profile1 | Command to make profile1 active. This command is needed to makes sure we can switch between profiles on the fly.|
   

   ### Bash script commands
   
   | Command        | Purpose      | 
   | ------------- |:-------------:|
   |Create empty file     | touch example.txt | 
   | make directory     | mkdir -p mydir      |  
   |remove file by force    | rm -f example.txt      |  
   
   
   ### k8 commands
   ### Other commands
   | | |
   |----- |:------:|
   | Add the following line to your .bash_profile file with a text editor: | alias ic='cd ~/Library/Mobile\ Documents/com~apple~CloudDocs'|
  |Open a new terminal window | ic |
   
     
   | Git Explain        | Git commands | followup |
   | ------------- |:-------------:| :-------------: |
   | Add files for the add | git add . | |
   |Git status command- Returns what is the status of the log entry | git status |
   |Getting all the log information| git log | |
   |Getting commit | git commit -a |Brings a VIM editor. 'I' will insert details and 'ESC' followed by ':wq' will exit editor| |
   | Getting commit with comment | git commit -am "Some comment to go with" | Commits without any vm editor |
  |Getting commit with comment | git show --oneline  | Shows all commits in one line|
  |Getting dirty with the Git branches | git commit --am "starting this module now" | | 
  |Git utility command for status |git log --online --all --graph| Gives a graphical view of the command and commits made |
  
   
