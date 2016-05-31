Zookeeper
=================
Using jplock's zookeeper

     https://github.com/jplock/docker-zookeeper


Zookeeper start for one
=================    
 docker run -d -p 2181:2181 -p 2888:2888 -p 3888:3888 镜像ID     

--net=host 要慎用，因为封装的不完整。 
 docker run -d --net=host 镜像ID    


     
     
