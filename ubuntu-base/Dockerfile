from ubuntu

# 修改源
RUN echo 'deb http://mirrors.163.com/ubuntu/ precise main restricted\n \
deb-src http://mirrors.163.com/ubuntu/ precise main restricted\n \
deb http://mirrors.163.com/ubuntu/ precise-updates main restricted\n \
deb-src http://mirrors.163.com/ubuntu/ precise-updates main restricted\n \
deb http://mirrors.163.com/ubuntu/ precise universe\n \
deb-src http://mirrors.163.com/ubuntu/ precise universe\n \
deb http://mirrors.163.com/ubuntu/ precise-updates universe\n \
deb-src http://mirrors.163.com/ubuntu/ precise-updates universe\n \
deb http://mirrors.163.com/ubuntu/ precise multiverse\n \
deb-src http://mirrors.163.com/ubuntu/ precise multiverse\n \
deb http://mirrors.163.com/ubuntu/ precise-updates multiverse\n \
deb-src http://mirrors.163.com/ubuntu/ precise-updates multiverse\n \
deb http://mirrors.163.com/ubuntu/ precise-backports main restricted universe multiverse\n \
deb-src http://mirrors.163.com/ubuntu/ precise-backports main restricted universe multiverse\n \
deb http://mirrors.163.com/ubuntu/ precise-security main restricted\n \
deb-src http://mirrors.163.com/ubuntu/ precise-security main restricted\n \
deb http://mirrors.163.com/ubuntu/ precise-security universe\n \
deb-src http://mirrors.163.com/ubuntu/ precise-security universe\n \
deb http://mirrors.163.com/ubuntu/ precise-security multiverse\n \
deb-src http://mirrors.163.com/ubuntu/ precise-security multiverse\n \
deb http://extras.ubuntu.com/ubuntu precise main\n \
deb-src http://extras.ubuntu.com/ubuntu precise main' > /etc/apt/sources.list

#更新配置
RUN apt-get update && apt-get upgrade && apt-get install -y vim wget && rm -rf /var/lib/apt/lists/*