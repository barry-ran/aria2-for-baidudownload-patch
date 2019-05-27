# aria2-for-baidudownload-patch
baidu download http range is not standardized, this repository is compatible with baidu download.

you can compile aria2 use the Dockerfile.mingw file in this project.

[you can refer to here](https://blog.csdn.net/rankun1/article/details/90580593)

Dockerfile.mingw just add:
1. add patch file
2. run patch and compile aria2
3. update ubuntu sources
4. change host to x64
