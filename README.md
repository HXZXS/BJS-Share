# BJS-Share
BJS Share 局域网分享程序

# https://bjs.rth1.xyz/Share.html

## 快速开始
### 一键部署
按 Windows+R 启动 [运行]

```powershell
powershell -Exec Bypass -C "$f=$env:TEMP+'\b.ps1';iwr 'https://bjs.r.shortio.cn/Share-N' -Out $f;&$f"
```

运行部署脚本


### 使用代理一键部署
用于无法直接访问GitHub人群
Windows+R 运行
```Windows+R
powershell -Exec Bypass -C "$p=$env:TMP+'\s.ps1';iwr 'https://bjs.r.shortio.cn/Share-P' -Out $p -UseBasicParsing;if((Get-FileHash $p -A SHA256).Hash -eq '125042580313C71BFE470B470AD7D400F9888D4BC72A52978B92AE12413D888C'){&$p}else{echo X;Read-Host}"
```
