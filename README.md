# gdock-ci
gdock OpenWrt 自动编译环境使用方法：
1. 编辑diy.sh，自定义固件。（不会修改或者不想自定义，可忽略此步骤）
2. 自行在本地生成 .config 文件，或者直接使用我生成好的这个配置文件。
3. push .config 文件，或者直接在github页面上编辑。
（特别提示，如果大雕有新代码，你就修改一下 .config的第一行的日期就会自动编译了）

我已生成的默认.config配置包含以下内容：

1. 全家桶（多个app，不逐一列举了）
2. 多主题：Argon Netgear Material Bootstrap
3. ipv6支持
4. usb3.0支持
5. ntfs文件系统支持
6. Frp内网穿透
7. MWAN3分流助手
8. qbittorrent
9. OpenVPN服务器
10. transmission的web-ui、ariang、yaaw
11. luci-app-cifsd

# 鸣谢P3TERX的抛砖引玉。
大佬的Blog: https://p3terx.com
# 鸣谢大雕的源码。
https://github.com/P3TERX/Actions-OpenWrt
