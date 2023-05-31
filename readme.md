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
</pre>

