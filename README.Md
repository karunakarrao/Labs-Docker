Docker :
------------
$ systemctl status docker
$ service docker status
$ systemctl start/stop/restart docker
$ systemctl enable docker
$ systemctl cat docker

$ journalctl -u docker  
$ journalctl -uf docker.service --> follow the log file.

$ ps -ef|grep docker

$ docker version
$ docker ps -a/-q/-s/-f/
$ docker login/logout

