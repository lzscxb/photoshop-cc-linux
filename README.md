# photoshop-cc-linux

仅供个人学习，下载后请在一小时内删除！
基于 Wine7 版本 打包的 photoshop cc 2017

# 安装
## 依赖
**Archlinux:**
> wine 版本为 `7.0rc1-1`
```
yay -S wine wine-gecko wine-mono
```

**下载软件包并解压**
https://github.com/lzscxb/photoshop-cc-linux/releases
```
tar -zxvf photoshop_cc2017_linux_2022-01-01.tar.gz
```

## 方式一
1. 下载依赖
```
yay -S zenity
```

2. 执行 setup.sh
```
cd photoshop_cc2017_linux_2022-01-01
./setup.sh
```
安装提示饥即可完成安装

## 方式二
手动安装
```
cd photoshop_cc2017_linux_2022-01-01
# 解压 app.tar.gz 包
tar -zxvf app.tar.gz

# 移动软件包
mv photoshop /opt
cp photoshop/setup.sh /opt/photoshop/setup.sh

# 生成桌面快捷方式
cp /opt/photoshop.desktop ~/.local/share/applications/photoshop.desktop
```
