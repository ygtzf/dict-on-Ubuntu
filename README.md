# dict-on-Ubuntu
setup of dictionary on ubuntu


Ubuntu下字典的使用
#####################

星际字典安装及使用：
____________________
1.安装

::

    1. apt-get install stardict
    2. 下载字典库包，地址是
    http://kdr2.com/resource/stardict.html
    有很多词库，wget到本地
    3. 安装词库：
    tar jxf  stardict-gaojihanyudacidian_fix-2.4.2.tar.bz2   -C /usr/share/stardict/dic
    4. 下载并安装发音包：
    wget https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/stardict-3/WyabdcRealPeopleTTS.tar.bz2
    sudo tar jxf WyabdcRealPeopleTTS.tar.bz2 -C /usr/share/
2. 比较不错的字库：

::

    stardict-21shijishuangxiangcidian-2.4.2.tar.bz2
    stardict-kdic-computer-gb-2.4.2.tar.bz2
    stardict-xdict-ce-gb-2.4.2.tar.bz2
    stardict-xdict-ec-gb-2.4.2.tar.bz2
