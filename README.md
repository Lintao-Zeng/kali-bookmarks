1、创建热点
```batch
sudo create_ap wlan0 eth0 test -w2  666666666 &
```

2、立即启动服务
```batch
sudo systemctl start create_ap
```

3、开机自启
```batch
systemctl enable create_ap
```
4、常见错误

4.1: Failed to initialize lock
```batch
sudo rm -rf /tmp/create_ap.all.lock
```

[Linux 建立文件夹的链接 - Yemilice - 博客园](https://www.cnblogs.com/Yemilice/p/6217285.html)

[Apache启动失败 DefaultRuntimeDir must be a valid directory, absolute or relative to ServerRoot_aijie099的专栏-CSDN博客](https://blog.csdn.net/aijie099/article/details/111828295)

[安装和配置 Samba | Ubuntu](https://ubuntu.com/tutorials/install-and-configure-samba#1-overview)

[Create Hotsopt on Kali linux](https://forums.kali.org/showthread.php?4643-Create-Hotsopt-on-Kali-linux)

[wireless - hostapd error "nl80211: Could not configure driver mode" - Ask Ubuntu](https://askubuntu.com/questions/472794/hostapd-error-nl80211-could-not-configure-driver-mode)

[“SIOCSIFFLAGS：由于RF-kill而无法进行操作”？ - Ubuntu问答](https://ubuntuqa.com/article/1570.html)

[linux开热点 - 矮_子 - 博客园](https://www.cnblogs.com/huangshengpeng/p/13860573.html)

[wireless - how to find out if my card supports infrastructure mode? - Ask Ubuntu](https://askubuntu.com/questions/106745/how-to-find-out-if-my-card-supports-infrastructure-mode)
