# Local DL 基础版（客户发行）

与自用开发版分开：`D:\cursor生成文件\bili-downloader` 是自用；本目录只发给客户。

## 功能
- 清晰度不限制
- 每天默认 10 次成功下载（`edition.js` → `dailyDownloadLimit`）
- 无去水印 / 无批量（高级版以后再开）
- **自动更新**（需配置 GitHub Releases，见 `自动更新说明.md`）

## 开发启动
```bat
npm install
npm start
```

## 打包给客户（推荐安装包，支持自动更新）
```bat
npm run dist
```
输出：`release\LocalDL-基础版-Setup-x.y.z.exe`  
把该 Setup 发给客户安装。

仅目录调试：
```bat
npm run pack
```
