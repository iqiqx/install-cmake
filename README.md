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
