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
   

   ### Bash script commands
   
   | Command        | Purpose      | 
   | ------------- |:-------------:|
   |Create empty file     | touch example.txt | 
   | make directory     | mkdir -p mydir      |  
   |remove file by force    | rm -f example.txt      |  
   
   
   ### k8 commands
   ### Other commands
   
     
   | Git Explain        | Git commands | followup |
   | ------------- |:-------------:| :-------------: |
   |Add files for the add    | git add . | |
   |Git status command- Returns what is the status of the log entry  | git status |
   |Getting all the log information | git log |
   |Getting commit | git commit -a |Brings a VIM editor. 'I' will insert details and 'ESC' followed by ':wq' will exit editor|
   |Getting commit with comment | git commit -am "Some comment to go with" |Commits without any vm editor|
   |Getting commit with comment | git show --oneline  |Shows all commits in one line|
   |Getting dirty with the Git branches | git commit --am "starting this module now" |
   |Doing a new branch here Git branches | git branch demo-master |