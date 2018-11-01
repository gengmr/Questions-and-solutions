# Questions-and-solutions
Questions I've ever meet and solutions

#### pip update fail:
首先解决python2和python3共存时候cmd中都是python的问题，可以进入Python3安装路径中将python.exe改成python3.exe, 这样cmd中可以用python进入python2,用python3进入python3,然后可以卸载掉python自带的pip，从网上找到最新的pip源码，用源码安装，即进入到setup.py文件路径中，用python3 setup.py install安装pip即可
