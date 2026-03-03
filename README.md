# Kirantest

install git 

sudo apt update
sudo yum update -y
sudo apt install git
git --version
git config --global user.name "naveenthammu"
git config --global user.email "naveenn610@gmail.com"

For generating token -
GitHub -> Settings -> Developer Settings -> Personal access tokens (classic). Click on your token and ensure repo (Full control of private repositories) is checked. Save it.

Format: git remote set-url origin https://<TOKEN>@github.com/<USER>/<REPO>.git
git remote set-url origin https://----------@github.com/naveenthammu/Kirantest.git

Example:
root@ip-172-31-15-31:/home/ubuntu/Kirantest# ls -ltr 
total 8
-rw-r--r-- 1 root root  365 Mar  3 12:19 README.md
drwxr-xr-x 4 root root 4096 Mar  3 12:19 EmployeeManagementSystem_Full_Project
root@ip-172-31-15-31:/home/ubuntu/Kirantest# git remote set-url origin https://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@github.com/naveenthammu/Kirantest.git
root@ip-172-31-15-31:/home/ubuntu/Kirantest# 
