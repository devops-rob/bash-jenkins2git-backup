# bash-jenkins2git-backup
Shell script that backs up jenkins configurations to git

This script requires a git repo called jenkins_backup to be created
You will need to add your ssh public key to the deploy keys of this newly created repo and allow read/write permissions
Clone the repo into /var/lib/ folder
Save this script to the /root/ folder
Setup a crontab to run this script as per your requirement.

This script is compatible with CentOS/Redhat servers
