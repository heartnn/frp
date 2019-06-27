### frps-onekey
此脚本根据[clangcn/onekey-install-shell](https://github.com/clangcn/onekey-install-shell/tree/master/frps)脚本制作，感谢`Clang`大大
#### 版本
```
脚本版本：19.06.27

frps版本：0.27.0
```
#### 安装
```
wget --no-check-certificate https://raw.githubusercontent.com/jakehu/frp/frps-onekey/master/install-frps.sh -O ./install-frps.sh

chmod 700 ./install-frps.sh

./install-frps.sh install
```
#### 卸载
```
./install-frps.sh uninstall
```
#### 更新
```
./install-frps.sh update
```
#### 管理
```
/etc/init.d/frps {start|stop|restart|status|config|version}
```
### frpc-docker

#### 版本
```
脚本版本：19.06.27

frps版本：0.27.0
```