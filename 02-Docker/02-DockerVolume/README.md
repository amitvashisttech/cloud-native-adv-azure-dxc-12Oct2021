```  
101  git add . ; git commit -m "01-Docker-Common" ; git push 
  102  docker volume ls 
  103  docker volume create my-vol
  104  docker volume ls 
  105  docker inspect volume my-vol
  106  docker volume inspect my-vol
  107  docker run -it --name test-vol1 -v my-vol:/amit ubuntu:16.04
  108  docker ps 
  109  docker kill $(docker ps -qa)
  110  ls
  111  docker volume inspect my-vol
  112  cd /var/lib/docker/volumes/my-vol/
  113  ls
  114  cd _data/
  115  ls
  116  cat hello.txt 
  117  docker ps -a 
  118  docker rm test-vol1
  119  docker ps -a 
  120  docker volume ls 
  121  cd ..
  122  ls
  123  cd _data/
  124  ls
  125  cat hello.txt 
  126  cd ..
  127  ls
  128  cd 
  129  ls
  130  docker pull nginx 
  131  docker images 
  132  docker image inspect 87a94228f133
  133  docker ps 
  134  docker run -d --name nginx 
  135  docker run -d --name nginx nginx
  136  docker ps 
  137  docker exec -it b73afdded5d4 ps -ef 
  138  docker run -it --name test-vol1 -v my-vol:/var/www/html/ nginx
  139  docker run -itd --name test-vol1 -v my-vol:/var/www/html/ nginx
  140  docker run -itd --name test-vol1 -v my-vol:/var/www/html/ nginx2
  141  docker run -itd --name test-vol2 -v my-vol:/var/www/html/ nginx
  142  ls
  143  docker ps 
  144  docker inspect test-vol2
  145  curl 172.17.0.3
  146  curl 172.17.0.3/amit.txt
  147  curl 172.17.0.3/var/www/html/amit.txt
  148  ls
  149  docker ps -a 
  150  docker kill $(docker ps -aq)
  151  docker rm $(docker ps -aq)
  152  ls
  153  docker run -d --name test-vol1 -v my-vol:/usr/share/nginx/html nginx
  154  docker run -d --name test-vol2 -v my-vol:/usr/share/nginx/html nginx
  155  curl 172.17.0.3
  156  curl 172.17.0.3/amit.txt
  157  curl 172.17.0.3/hello.txt
  158  curl 172.17.0.2/hello.txt
  159  > /var/lib/docker/volumes/my-vol/_data/hello.txt
  160  echo "Welcome to Docker Volume Demo" >> /var/lib/docker/volumes/my-vol/_data/hello.txt
  161  curl 172.17.0.2/hello.txt
  162  curl 172.17.0.3/hello.txt
  163  docker run -it --name test-ub-1 -v my-vol:/usr/share/nginx/html ubuntu:16.04
  164  curl 172.17.0.2/hello.txt
  165  curl 172.17.0.3/hello.txt
  166  docker run -it --name test-ub-2 -v my-vol:/usr/share/nginx/html:ro ubuntu:16.04
  167  ls
  168  docker kill $(docker ps -aq)
  169  docker rm $(docker ps -aq)
  170* 
  171  docker run -it --name test-ub-2 -v /usr/share/nginx/html ubuntu:16.04
  172  docker volume ls 
  173  docker volume inspect aca8dfd188a56a2895d586b101e6ff73a7e52dde693f5f04d23ad1a854728636
  174  cd /var/lib/docker/volumes/aca8dfd188a56a2895d586b101e6ff73a7e52dde693f5f04d23ad1a854728636/_data
  175  ls
  176  cat hello.txt 
  177  ls
  178  cd ..
  179  cd 
  180  ls
  181  docker ps 
  182  docker inspect test-ub-2
  183  ls
  184  docker kill $(docker ps -aq)
  185  docker rm $(docker ps -aq)
  186  ls
  187  docker volume ls 
  188  docker volume ls -1
  189  docker volume ls -q
  190  docker volume rm $(docker volume ls -q)
  191  docker volume ls 
  192  ls
  193  cd cloud-native-adv-azure-dxc-12Oct2021/
  194  ls
  195  cd 02-Docker/
  196  ls
  197  mkdir 02-DockerVolume
  198  history >> 02-DockerVolume/README.md
```
