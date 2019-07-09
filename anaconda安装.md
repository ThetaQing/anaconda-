# 辛酸血泪史  
之前装anaconda都很顺利，这次为了配置pytorch环境，一直安装不上pytorch环境下的Spyder，于是，我胸有成竹地卸载了我的anaconda，万丈高楼拔地起，开始从头开始。
噩梦也开始了……  
（1）先是安装Spyder的时候只能在base环境下安装，新创建的环境下Spyder都安装不了，不管是换python版本还是换Spyder版本，都没有用，所以我又把它卸载了，并且重启电脑  
（2）重新安装，这次，我选择安装在默认路径**C:\Users\User\Anaconda3**，并且在Navigate下安装，好歹还能报个错，Multiple Errors Encountered.搜索一下，试了很多种方法，没有结果。然后尝试在prompt下
pip install spyder更新一下，再启动Spyder，报错缺少Chardet模块，pip安装一下，(╯▽╰)，报一堆没有安装的包![](F:\Code\Github\Git\anaconda\module.png)  
![](https://github.com/ThetaQing/anaconda-/blob/master/module.png)  
接下来就是一个一个地安装了，然而结果还是报错  ![](https://github.com/ThetaQing/anaconda-/blob/master/start.png)  
(3)那我就按照它说的，reset一下吧，报错是没有，闪退又出现了，那，死马当活马医，pip更新一下Spyder吧，没想到！！！竟然可以了！！！amazing！！！  
![](https://github.com/ThetaQing/anaconda-/blob/master/ok.png)  

