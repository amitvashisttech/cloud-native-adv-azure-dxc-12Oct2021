```
    1  ls
    2  cd cloud-native-adv-azure-dxc-12Oct2021/
    3  ls
    4  cd 02-Docker/
    5  ls
    6  docker ps 
    7  docker pull ubuntu:16.04
    8  docker images 
    9  docker run -it ubuntu:16.04 
   10  docker ps 
   11  ls
   12  docker ps 
   13  docker ps -a
   14  docker start 1b1a84100ba8
   15  docker ps 
   16  docker run -it ubuntu:16.04
   17  docker ps 
   18  docker attach 1b1a84100ba8
   19  docker ps 
   20  docker run -it ubuntu:16.04
   21  docker ps 
   22  docker run -it ubuntu:16.04
   23  docker ps 
   24  docker exec -it 1b1a84100ba8 ps -ef 
   25  docker exec -it 1b1a84100ba8 cat /root/amit/*.txt
   26  docker exec -it 1b1a84100ba8 ls /root/amit/
   27  docker exec -it 1b1a84100ba8 cat  /root/amit/hello.txt
   28  docker exec -it 1b1a84100ba8 bash 
   29  docker ps 
   30  ls
   31  docker ps 
   32  docker ps -a 
   33  docker run -it --name webserver-1 ubuntu:16.04
   34  docker ps 
   35  docker attach webserver-1
   36  ls
   37  docker ps 
   38  docker inspect webserver-1
   39  curl 172.17.0.4
   40  docker attach webserver-1
   41  curl 172.17.0.4
   42  curl 172.17.0.4/hello.html
   43  ls
   44  history 
   45  docker ps 
   46  docker kill 1b1a84100ba8
   47  docker ps 
   48  ls
   49  docker ps -a 
   50  docker ps -aq 
   51  docker rm $(docker ps -aq)
   52  docker ps -a 
   53  ls
   54  cd 01-DockerCommon/
   55  ls
   56  history > README.md 
```
