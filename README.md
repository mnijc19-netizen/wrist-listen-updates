# 腕听更新

最新版本：0.5.5（Android 5.0+，针对 M60T / Android 9 优化）

[下载 APK](https://raw.githubusercontent.com/mnijc19-netizen/wrist-listen-updates/main/apks/WristListen-0.5.5-M60T.apk) · [版本说明](https://github.com/mnijc19-netizen/wrist-listen-updates/releases/tag/v0.5.5)

支持公开播客 RSS、网络电台、B站公开视频的独立音轨和本地音频导入。YouTube 链接交给外部 [NewPipe](https://newpipe.net/)，当前网络需要能访问 YouTube。部分海外来源和直播流可能不可用。

“普通省电”入口在获得系统授予的 WRITE_SECURE_SETTINGS 权限后直接切换普通省电；未授权时打开系统设置。安装 APK 本身不会自动获得该权限。它不修改 Wi-Fi 或蓝牙开关，不包含永久远程控制服务。

电池页区分全机运行内存、当前可用内存和腕听占用。剩余电量计读数不是实际满充容量，标准接口不能确认硬件充电保护。

此仓库只托管公开 APK 和版本信息，不包含签名私钥、收听记录或账号凭据。应用内更新会验证包名、版本、SHA-256 和签名。

更新接口：[latest.json](https://raw.githubusercontent.com/mnijc19-netizen/wrist-listen-updates/main/latest.json)
