
[Tutorial on setting up Ubuntu ec2 to server ipython notebook files](http://blog.impiyush.me/2015/02/running-ipython-notebook-server-on-aws.html)

1. Log in AWS Console
2. Log into your Ubuntu ec2 instance from the command line: "ssh -i ~/.ssh/[key.pem] ubuntu@ec2-xx-xxx-xxx.amazonaws.com"
3. Install your environment at this step. This may include 
- pip install -r 'requirements.txt' 
- anaconda for Linux 

  ```
  wget http://repo.continuum.io/archive/Anaconda2-4.1.1-Linux-x86_64.sh
  bash Anaconda2-4.1.1-MacOSX-x86_64.sh
  ```
4. 
