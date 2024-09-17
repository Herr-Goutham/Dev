# Develop
Git Commands:
> git config --global --list
> git config --global --unset
> git add <filename> 
> git add . (it defines file in present directory)
> git commit -m "adding file"
> git push origin main
> git pull
> git log --oneline
STAGES IN GIT:-
    - Working area/untracker area
    - Staging area/tracked area
    - Local repository

#Observability
Installing prometheus on linux - using Version 2.40.1
wget https://github.com/prometheus/prometheus/releases/download/v2.40.1/prometheus-2.40.1.linux-amd64.tar.gz
tar xvf prometheus-2.40.1.linux-amd64.tar.gz
cd prometheus-2.40.1.linux-amd64
./prometheus > /dev/null 2>&1 &
