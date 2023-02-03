# Simple Linux Desktop Environment

这是Cutefish Desktop Environment的一个分支，旨在提供简单高效的桌面体验

国内镜像：<https://gitcode.net/simple-linux-de> 请勿在此提交代码！

# Status

项目主要面对Ubuntu，目前处于初始阶段，仅提供unstable链接。

ubuntu-jammy 分支正在测试中！

__注意__ ：使用gitcode/github服务器的用户请尽快切换为新的地址！

CDN:
```shell
curl -Ss http://index.sl.300c.top/project/simplelinux.asc | sudo gpg --import -
sudo bash -c "gpg --export F5D1CCA2BD189758 > /etc/apt/trusted.gpg.d/simplelinux.gpg"
sudo bash  -c "echo 'deb [trusted=yes] http://index.sl.300c.top unstable main contrib non-free' > /etc/apt/sources.list.d/simplelinux.list"
```

欢迎大家贡献代码！也欢迎大佬们加入开发~

P.S. 目前@ganyuanzhen（也就是我）在Deepin上面开发，所以大概会有个基于Deepin的版本？

# Some screenshots

Terminal

![Terminal](profile/imgs/terminal.png)
