```  
201  git add . ; git commit -m "01-Docker-Common" ; git push 
  202  ls
  203  cd cloud-native-adv-azure-dxc-12Oct2021/
  204  ls
  205  cd 02-Docker/
  206  ls
  207  mkdir 03-DockerImages
  208  ls
  209  cd 03-DockerImages/
  210  ls
  211  vim Dockerfile
  212  ls
  213  vim app.py 
  214  vim 
  215  vim req.txt
  216  ls
  217  cat app.py 
  218  ls
  219  cat req.txt 
  220  ls
  221  vim Dockerfile 
  222  ls
  223  docker build -t mypython-web-app:v4 . 
  224  docker images 
  225  docker run -d --name test-1 mypython-web-app:v4
  226  docker run -d --name test-2 mypython-web-app:v4
  227  docker ps 
  228  docker inspect test-1
  229  curl 172.17.0.2
  230  curl 172.17.0.2:8081
  231  curl 172.17.0.2:8081/hello
  232  curl 172.17.0.2:8081/info
  233  curl 172.17.0.3:8081/info
  234  docker ps 
  235  ls
  236  docker login 
  237  docker ps 
  238  docker images 
  239  docker push mypython-web-app:v4
  240  docker tag  297374bf6b8c  amitvashist7/mypython-web-app:v4
  241  docker images 
  242  docker push amitvashist7/mypython-web-app:v4 
  243  docker ps 
  244  ls
  245  history 
  246  history >> README.md
```
