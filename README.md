# MAX · 跑回现实

《怪奇物语》同人小游戏，帮助 Max 躲避碎石、收集音符、跑出异世界。

## 操作

- ↑ / ↓ 或 W / S：换道
- 空格：跳跃
- E：能量满后冲刺
- P / Esc：暂停或继续
- 手机可使用画面下方按钮

## 音乐现状

歌曲来源为 Kate Bush 官方 SoundCloud 播放器，歌曲为《Running Up That Hill (A Deal With God) (2018 Remaster)》。原曲音频没有打包在本仓库中。当前测试环境未能成功播放该外部音源，此问题尚未解决；播放器会显示失败提示。可选择设备上的本地音频，文件不会上传。朋友的台词是游戏提示字幕，没有模拟演员配音。

## GitHub Pages

本仓库根目录为可直接访问的网页。GitHub Pages 发布目录为 `main` 分支的 `/(root)`。

完整 React / TypeScript 源码在 [max-run-back-home-source.zip](./max-run-back-home-source.zip) 中。下载并解压后即可开发；源码项目的 `docs/` 是构建产物。

## 本地开发

需要 Node.js 22.13 或更高版本。

```sh
npm ci
npm run dev
npm run typecheck
npm run build
```

修改源文件后运行 `npm run build`。将 `docs/` 内的文件发布到仓库根目录；如果将 `assets/` 文件移到根目录，也需同步调整 `index.html` 和 CSS 中的资源路径。

在线游玩：https://ruyuehan-27.github.io/max-run-back-home/

此项目为非官方同人作品；剧集、角色及歌曲属于各自权利人。
