Design Devops 1
<pre>

history
    Console sign-in URL
    https://685421549691.signin.aws.amazon.com/console
    user-walmart-3
    Console password
    ysU55p[P
    
    EC2. > Instances > select kiran instance > start > 
    i-0da672616841226b4
    Connect to instance
    copy connect comand 
    
    got to terminal having keyvalue pair for above
    hit command run on terminal



Design DevOps
yum install git -y
git --version
git config --global user.name "maz"
git config --global user.email "mazyafai@gmail.com"
git config --global --list
pwd
cd /home/ec2-user
ls
mkdir maz
ls
cd maz/
ls
git status
git init
git status
touch f1
ls
echo "hello everyone" > f1
cat f1
git add .
git status
git commit -m "first commit"
git status
git remote add origin https://github.com/MAZYAFAI/devops-usa.git
git push origin master
give your user id 
for password give token   Git hub token: (ur hithub > settings > dev settings > create token > select all > save) 
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


[ec2-user@ip-172-31-36-134 ~]$ sudo -i

yum install update -y
    2  yum install docker  -y
    3  docker --version
    4  service docker status
    5  service docker start
    6  service docker status
    7  docker info
    8  docker images
    9  docker ps
   10  docker ps -a
   > list all info of docker > dockerId listed that like your new VM/box
   11  docker pull ubuntu
   12  docker images
   13  docker run -it --name c1 ubuntu /bin/bash
    ... inside docer so below don't work > exit
   14  docker images
   15  docker ps
   16  history
   17  docker search nginx
   18  docker pull nginx
   19  docker images
   20  docker run -it --name c2 nginx /bin/bash
   .. exit from above to run below
   21  docker ps
   23  docker run -it --name c3 php /bin/bash
   .. exit
   24  docker ps
   25  docker ps -a
   26  docker start c3
   27  docker ps
   28  docker attach c3
   29  docker diff c3
   30  docker ps
   31  docker commit c3 c3img
   32  docker images
   33  docker run -it --name c4 c3img /bin/bash
   
   
day2 continue. 
port mapping 
       docker ps
   47  docker images
   48  docker rm -f c1 c2 c3 c4 c5
   49  docker ps
   50  docker rmi -f ubuntu php nginx c3img newimg
   51  docker images
   52  docker ps
   53  docker run -td --name server1 -p 80:80 ubuntu
   enable aws > console > security > allow all traffic >
   
   54  docker ps
   55  docker port server1
   56  docker exec -it server1 /bin/bash
ls
    2  apt-get update -y
    3  apt-get install apache2 -y
    4  service apache2 restart
    5  cd /var/www/html
    6  ls
    7  cat index.html
    8  echo "we are learning port mapping concept in docker today" > index.html
    9  cat index.html
    
    
    
    
----day 2 history

docker ps
   47  docker images
   48  docker rm -f c1 c2 c3 c4 c5
   49  docker ps
   50  docker rmi -f ubuntu php nginx c3img newimg
   51  docker images
   52  docker ps
   53  docker run -td --name server1 -p 80:80 ubuntu
   54  docker ps
   55  docker port server1
   56  docker exec -it server1 /bin/bash
ls
    2  apt-get update -y
    3  apt-get install apache2 -y
    4  service apache2 restart
    5  cd /var/www/html
    6  ls
    7  cat index.html
    8  echo "we are learning port mapping concept in docker today" > index.html
    9  cat index.html

Maz Yafai to Everyone (May 31, 2023, 1:59 PM)
docker run -td --name server2 -P nginx
   59  docker ps
   60  docker port nginx
   61  docker port server2
   62  docker run -td --name server3 -p 8080:8080 jenkins/jenkins
   63  docker ps
   64  docker port server3
   65  docker exec -it server3 /bin/bash
go to browser  
http://13.233.183.53:8080/

</pre>

