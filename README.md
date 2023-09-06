# Github_Note

Command list for Github

#git clone < SSH Key >
 - Download the code from github

#git status
 - Shows all the file that are updated

#git add . / git add README.md.
 - Track the new created file
 - "." mean all the file

#git commit -m "< message >" -m "< message >"
 - Add the commends for the commit 
 - the first message is the title
 - second is the description

#git config --global user.email "email@gmail.com"
 - Add the account user for the commit mesage

#git push
 - Upload the changed file to the Github

#ssh-keygen -t rsa -b 4096 -C "< email for github >"
 - There is two file will be generated
 - key | key.pub 
 - key.pub need to be uploaded to Github

#ssh-add -K ~/.ssh/id_rsa