# Brook 端口转发 一键脚本
原 逗比 Brook 端口转发 一键管理脚本 修改版
支持动态域名，开启监控后可自动更新域名IP。

## SXR666 再修改分支
尝试修复 https://github.com/yulewang/brook/issues/4 此分支的问题
尝试修复 https://github.com/ECIAP/brook/issues/1 此分支的问题

### 从GitHub拉取
```
For RHEL / CentOS:
yum install bind-utils wget -y && https://raw.githubusercontent.com/SXR666/brook-pf/main/brook-pf-mod.sh && chmod +x brook-pf-mod.sh && bash brook-pf-mod.sh

For Debian / Ubuntu
apt install dnsutils wget -y && https://raw.githubusercontent.com/SXR666/brook-pf/main/brook-pf-mod.sh && chmod +x brook-pf-mod.sh && bash brook-pf-mod.sh
```
