# centos7-install-latest-gcc

sudo yum install -y centos-release-scl
sudo yum install -y devtoolset-9-gcc devtoolset-9-gcc-c++

# 安装了之后,并没有替换旧的,所以这里选择连接到最新的gcc/g++
echo "source /opt/rh/devtoolset-9/enable" >> /etc/profile
source /etc/profile
