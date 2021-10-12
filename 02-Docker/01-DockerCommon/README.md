```
    1  git clone https://github.com/amitvashisttech/cloud-native-adv-azure-dxc-12Oct2021.git
    2  ls
    3  cd cloud-native-adv-azure-dxc-12Oct2021/
    4  s
    5  ls
    6  git config --global credential.helper 'cache --timeout=360000'
    7  mkdir 02-Docker/00-Setup/ -p 
    8  ls
    9  cd 02-Docker/00-Setup/
   10  ls
   11  vim install-docker.sh 
   12  chmod +x install-docker.sh 
   13  ls
   14  ./install-docker.sh 
   15  docker version 
   16  ls
   17  cd ..
   18  ls
   19  cd ..
   20  ls
   21  git add . ; git commit -m "02-Docker" ; git push 
   22  git config --global user.name "Amit Vashist"
   23  git config --global user.email "amitvashist7@outlook.com"
   24  git add . ; git commit -m "02-Docker" ; git push 
   25  docker run busybox echo "Hello World"
   26  docker ps 
   27  docker container ls 
   28  docker container ls -a 
   29  docker ps -a 
   30  docker images 
   31  ls
   32  cd 02-Docker/
   33  ls
   34  mkdir 01-DockerCommon
   35  cd 01-DockerCommon/
   36  ls
   37  history >> README.md

```
