# aapanel_6.8.27
aapanel_6.8.27 降级

安装官方aaPanel v6.8.37
```
wget -O install.sh https://raw.githubusercontent.com/789cn/aapanel_6.8.27/refs/heads/main/install_aapanel.sh && sudo bash install.sh aapanel
```
或官方源
```
wget -O install.sh https://github.com/aaPanel/aaPanel/releases/download/6.8.37/install_aapanel.sh && sudo bash install.sh aapanel
```

aapanel_v6.8.37 最后的V6版本,不建议降级
以下备用!
-------------------------- ------
降级为 aapanel6.8.27 版本

```
wget -O /root/update6_en.sh https://raw.githubusercontent.com/789cn/aapanel_6.8.27/refs/heads/main/update6_en.sh && sed -i 's/LinuxPanel_EN-${version}.zip/LinuxPanel_EN-6.8.27.zip/g' /root/update6_en.sh && bash /root/update6_en.sh && rm -rf /root/update6_en.sh
```
或官方源
```
wget -O /root/update6_en.sh https://download.bt.cn/install/update6_en.sh && sed -i 's/LinuxPanel_EN-${version}.zip/LinuxPanel_EN-6.8.27.zip/g' /root/update6_en.sh && bash /root/update6_en.sh && rm -rf /root/update6_en.sh
```
中文语言包 没啥用
```
wget -O aapanel_chinese.zip https://github.com/gacjie/aapanel_chinese/releases/download/6.8.27/aapanel_simplified_chinese_6827.zip && unzip -o aapanel_chinese.zip -d /www/server/ && /etc/init.d/bt restart
```
我的备份
```
wget -O aapanel_chinese.zip https://github.com/789cn/aapanel_6.8.27/releases/download/6.8.27/aapanel_simplified_chinese_6827.zip && unzip -o aapanel_chinese.zip -d /www/server/ && /etc/init.d/bt restart
```
