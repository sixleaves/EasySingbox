*注意：如果你的后端没有科学环境，规则地址前记得添加镜像否则无法拉取。  
例如：  
```
https://ghp.ci/https://raw.githubusercontent.com/qichiyuhub/rule/refs/heads/master/config/singbox/config_tproxy.json
```
openwrt运行singbox需求版本和依赖  

固件版本:  
OpenWrt >= 23.05  
firewall4

必要依赖：  
ca-bundle  
curl  
yq  
firewall4  
ip-full  
kmod-inet-diag  
kmod-nft-tproxy  
kmod-tun  