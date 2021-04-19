# `vmware` and `ubuntu`

[TOC]



#### 1、`vmware`篇

##### 综述：

> 要在虚拟机中安装`os` 的话，要准备`os镜像` ，`vmware虚拟机` 两个东西。接下来， 根据一定的教程就可以顺利的安装了。

##### 零件准备：









#### 2、`ubuntu`篇

##### 具体优化：

> 这个操作系统里面，有很多地方需要优化。:sailboat: 

1、当你第一次全屏显示的时候，你会发现OS在屏幕的正中央！四周都是大黑边！杂解决呢？

这个时候需要安装`vmtools`。





##### 软件推荐：

1、`linux`下的[VisualStudio](https://visualstudio.microsoft.com/zh-hans/)---------------[MonoDevelop](https://www.monodevelop.com/)

> 在安装这个`IDE` 安装之前，需要安装[Mono](https://www.mono-project.com/)(环境)
>
> 具体的安装方法就在`Mono` 的官网(下面MonoDevelop的🔗)





2、linux下最好的pdf-----------[Okular](https://okular.kde.org/)

```shell
sudo apt install okular
```







3、最好的`javaIDE` ------------[IDEA](https://www.jetbrains.com/idea/)

> 1、安装java的运行环境
>
> ```shell
> sudo apt install openjdk-8-jdk
> ```
>
> 2、安装`idea` 







4、最好的`markdown` 软件---------------[Typora](https://www.typora.io/)

```sh
# or run:
# sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys BA300B7755AFCFAE
wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -
# add Typora's repository
sudo add-apt-repository 'deb https://typora.io/linux ./'
sudo apt-get update
# install typora
sudo apt-get install typora
```













5、