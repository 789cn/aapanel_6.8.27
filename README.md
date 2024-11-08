# aapanel_6.8.27
aapanel_6.8.27 降级
安装官方aaPanel v6.8.37
https://github.com/aaPanel/aaPanel/releases/download/6.8.37/install_aapanel.sh
```
bash install_aapanel.sh
```
降级为 aapanel6.8.27 版本
```
wget -O /root/update6_en.sh https://raw.githubusercontent.com/789cn/aapanel_6.8.27/refs/heads/main/update6_en.sh && sed -i 's/LinuxPanel_EN-${version}.zip/LinuxPanel_EN-6.8.27.zip/g' /root/update6_en.sh && bash /root/update6_en.sh && rm -rf /root/update6_en.sh
```
