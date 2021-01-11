# ps2 入坑指南 （完全新手向）

# playstation2 set-up guide (noob friendly)

## **目录**

[机型](#1机型models)
[配件](#2配件accessories)
[破解](#3破解soft-mod)
[配置网络硬盘Windows](#windows10篇)
[配置网络硬盘Linux](#linux篇)




## **1.机型(models)**

因为是新手向指南，这里不会详细列举每种机型，你只需要知道3件事情

1. 
    >厚机(fat):厚机体积很大，能加装硬盘的，但是不推荐，因为网线接口不是内置的。

    >![fat](https://gitee.com/waizui/ps2guide/raw/main/images/220px-PS2-Fat-Console-Set.jpg)



2. 
    >薄机(slim)：体积小，不能装硬盘，有网线口，推荐。

    >![slim](https://gitee.com/waizui/ps2guide/raw/main/images/250px-PS2-Slim-Console-Set.jpg)

> Q:为什么要装硬盘?
>>A:因为ps2原本是没有硬盘的，不像现在的游戏主机有内置硬盘，ps2的的游戏储存在DVD光盘中,玩游戏时必须放入光盘。后来被破解以后，可以通过加装硬盘的方式来直接加载游戏，而不用每次放入DVD光盘。

> Q:一定要装硬盘才能够玩吗?
>>A:不，可以不用硬盘，破解后的ps2，可以使用U盘，网络硬盘来加载游戏，不一定非要硬盘.

3. 
    >型号(Model No):无论哪种机型都对应一个具体的型号，这个型号很重要，在某些较高型号的机型上，这里要说的破解方式是用不了的。机型越高，发售时间越晚。查看机型在ps2主机后面的标签上,配图红圈中为本人的ps2型号。

    >![model_no](https://gitee.com/waizui/ps2guide/raw/main/images/modelNo.jpg)

> Q:各个机型之间有性能差别吗?
>>A:没有，或者说我不知道，据我所知，所有机型都可以玩所有的ps2游戏。


> Q:我该买什么型号?
>>A:不要买90xxx的型号，这个型号有些会无法破解，最好是700xx型号，就是我的那个版本，7开头，兼容性好，库存量大，便宜。

## **2.配件(accessories)**

以下是几个游玩的基本配件

1. 
    >手柄（controller):有线无线皆可，ps2的手柄存在摇杆飘移的问题，如果有条件可以买稍微好一点的原装手柄，下图四为本人的手柄，淘宝垃圾19.9包邮组装无线手柄，左右摇杆均轻微飘逸，但也可以用，只是对FPS类游戏真的不友好。

    >![contorller](https://gitee.com/waizui/ps2guide/raw/main/images/controller.jpg)

2. 
    >记忆卡（memoryCard）:ps2的唯一内置储存介质，游戏存档和系统设置都存在里面，越大越好，淘宝很多，十几块钱。此外你还必须买另外一张记忆卡，里面装得有FMCB，用来破解，也很便宜，几十块钱。ps2可以插两张记忆卡，其中一张，是用来破解的，装有FMCB的特殊记忆卡，这张卡插在1号记忆卡插口。如何破解在后面说，非常简单。

    >![memoryCard](https://gitee.com/waizui/ps2guide/raw/main/images/memorycard.jpg)
z
1. 
    >视频线(video cable):ps2支持几种视频输出格式，这里我只推荐两种  
        
    >1.分量色差线(component cable)：也是是色差端子，部分电视有色差接口，优点是画质清晰，缺点是不好转接到显示器（转接器贵），且有一部分电视不支持。ps2不附带此线，一般需要另外购买。配图是我用的色差端子，长这样:
    >>![componentCable](https://gitee.com/waizui/ps2guide/raw/main/images/componentcable1.jpg)
    >>购买分量线时要注意你的电视机后面有没有这样的五个插口，上面写得有Pr，Pb,y
    >>![componentCable1](https://gitee.com/waizui/ps2guide/raw/main/images/componentcable.jpg)

    >2.AV线(composite cable)：也就是最常见的电视机视频线，优点是兼容性好，几乎所有电视都可以接AV线，并且转接器便宜，缺点是画质很糊，不清晰，不过很多追求原汁原味的人都用AV线，一般买ps2会附赠一条AV线。
    >>![compositeCable](https://gitee.com/waizui/ps2guide/raw/main/images/avcable.jpg)

> Q:转接器什么意思?
>>A:无论是分量线，还是AV线，这些都不是为电脑显示器设计的，一般只有电视机才有相应的接口，如果想要在电脑显示器上显示ps2输出的画面，那就需要把这些线转为电脑显示器信号，就会用到转接器一般来说时HDMI，AV转接器比较便宜，色差转接器比较贵。

## **3.破解(soft mod)**

很多新手都关心破解是不是非常难，其实非常简单，只需要在淘宝买一个装得有FMCB的记忆卡就可以了，然后插在记忆卡插槽的1号位置，现在这种卡又是记忆卡，又可以启动破解系统。买的时候要注意下面两个问题。

1. 本文只推荐通过网络硬盘加载游戏，所以你买的FMCB记忆卡里，要包括OPL这个程序,可以问卖家。
    
    OPL  这是一个加载程序，可以从别的储存介质里面加载游戏，U盘，硬盘，或者网络硬盘。我目前使用的版本是 v0.9.3 这个版本比较稳定，用新版（比如v1559）时，有的游戏加载不了，战神1会卡在潘多拉神殿
      >![opl](https://gitee.com/waizui/ps2guide/raw/main/images/opl.jpg)
2. 插上FMCB记忆卡后，打开ps2，就可以直接启动OPL，按下左右方向键，然后进入选择游戏界面，当然，需要提前配置好你的储存介质。

## **4.配置网络硬盘**

配置网络硬盘会分为两部分，配置Windows10的网络硬盘（新手向），配置Linux的网络硬盘(进阶)。

> Q:我可以用U盘吗?
>>A:可以，但是不推荐，ps2的USB接口非常老，速率很低，用U盘玩会导致游戏频繁的在加载，丧失了乐趣。

### Windows10篇

>1.建立一个名为ps2smb的文件夹，注意路径最好是全英文。右键该文件夹，选择属性->共享->共享，添加一个叫做everyone的账户,然后点击共享。![eveyone](https://gitee.com/waizui/ps2guide/raw/main/images/everyone.png)

>2.打开: 打开控制面板->程序和功能->启用或关闭Windows功能->SMB1.0/Cifs文件共享支持,勾选图中的选项。![panel](https://gitee.com/waizui/ps2guide/raw/main/images/controlpanel.png)

>3.在网络和共享中心中，将有密码保护的共享关闭。![closepwd](https://gitee.com/waizui/ps2guide/raw/main/images/localnetwork.png)

>4.win+r 键，输入cmd然后回车，然后再在弹出的窗口输入ipconfig回车。![cmd](https://gitee.com/waizui/ps2guide/raw/main/images/cmd.png)![ipconfig](https://gitee.com/waizui/ps2guide/raw/main/images/ipconfig.png)
    记下图中的ipv4地址，待会儿要用。

>5.打开ps2，在背后插入你家的路由器接出来的网线，选中opl进入，按下手柄start键进入设置，然后按圆圈键选择网络设置。
    >>进入设置后，将下图1处的地址配置为192.168.0.10，IP地址模式设置为静态。将2处的地址填上刚刚记下的ipv4地址，将共享处填上ps2smb,将使用者填上guest,密码不用填,完成后点重新连接，如果连接失败，可能是地址被占用。可以将1处的地址最后一位数换一下再试。成功后返回，点击保存设置，不然下次启动还需要配置ip地址。
    ![ps2conf](https://gitee.com/waizui/ps2guide/raw/main/images/congtest1.png)

>6.回到电脑，你会看到刚刚建立的ps2smb文件夹下多了许多文件夹，其中有一个叫做DVD的文件夹，所有你从网上下载的ps2游戏，都是以iso为后缀名的，放到这个文件夹下面，ps2会自动识别。![DVD](https://gitee.com/waizui/ps2guide/raw/main/images/dvdFolder.png)

>7.放入游戏后，在ps2中，进入opl后，选择ETH游戏，就能看到你刚刚放入的游戏，圆圈键运行。这里推荐一个下载游戏ISO的网站<https://www.oldmanemu.net/%e5%ae%b6%e6%9c%ba%e6%b8%b8%e6%88%8f/ps2/ps2%e4%b8%ad%e6%96%87%e6%b8%b8%e6%88%8f%e5%85%a8%e9%9b%86>
![game](https://gitee.com/waizui/ps2guide/raw/main/images/games.jpg)

### Linux篇
如果你有使用linux的需求，我假定你已经懂了基本的知识。本人的测试机为树莓派3b+,系统为raspbian外挂硬盘，分区为ntfs。以下命令对于Debian系通用。

在你的ntfs分区上建立一个ps2smb的文件夹.

安装samba

    sudo apt install samba

编辑samba.conf 使用你自己熟悉的编辑器,这里使用vim

     sudo vim /etc/samba/smb.conf
在尾部追加图中的文字,忽略蓝色部分，那是注释

![smb](https://gitee.com/waizui/ps2guide/raw/main/images/smb.png)

其中，将path改为你自己的ps2smb文件夹的路径,保存退出

然后重启samba
    
    sudo service smbd restart
打开ps2，插入网线，选中opl进入，按下手柄start键进入设置，然后按圆圈键选择网络设置。进入设置后，将下图1处ps2的IP地址配置为你想要的地址，IP地址模式设置为静态。将2处的地址填上开启samba服务的linux服务端地址，将共享处填上ps2smb,将使用者填上任意字符,密码不用填,完成后点重新连接，成功后返回，点击保存设置，不然下次启动还需要配置ip地址。
![ps2conf](https://gitee.com/waizui/ps2guide/raw/main/images/congtest1.png)

回到电脑，你会看到刚刚建立的ps2smb文件夹下多了许多文件夹，其中有一个叫做DVD的文件夹，所有你从网上下载的ps2游戏，都是以iso为后缀名的，放到这个文件夹下面，ps2会自动识别。

![ps2folder](https://gitee.com/waizui/ps2guide/raw/main/images/linuxFolder.png)

放入游戏后，在ps2中，进入opl后，选择ETH游戏，就能看到你刚刚放入的游戏，圆圈键运行。这里推荐一个下载游戏ISO的网站<https://www.oldmanemu.net/%e5%ae%b6%e6%9c%ba%e6%b8%b8%e6%88%8f/ps2/ps2%e4%b8%ad%e6%96%87%e6%b8%b8%e6%88%8f%e5%85%a8%e9%9b%86>
![game](https://gitee.com/waizui/ps2guide/raw/main/images/games.jpg)
