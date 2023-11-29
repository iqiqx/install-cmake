# install-cmake

## 步骤：
1.下载二进制CMake文件 官方下载页面：https://cmake.org/download/

2.解压cmake文件包:
tar -xvf cmake-xx.tar.gz

3.移动到系统文件目录内:
mv cmake-xx /usr/local/cmake

4.写入终端环境并更新:
path echo 'export PATH="/usr/local/cmake/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

5.cmake --version

## 更新版本
重复1 2 3

# centos7-install-latest-gcc
1.sudo yum install -y centos-release-scl
2.sudo yum install -y devtoolset-9-gcc devtoolset-9-gcc-c++

安装了之后,并没有替换旧的,所以这里选择连接到最新的gcc/g++
3.echo "source /opt/rh/devtoolset-9/enable" >> /etc/profile source /etc/profile
