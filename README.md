# 药店广播智能体 - 面试展示版

在线演示：<https://2919401449-sys.github.io/drugstore-speaker-demo/>

这是一个可独立打开的静态展示页，不依赖 Python 后台、摄像头、DeepSeek API 或天气 API。

## 本地查看

双击打开 `index.html` 即可。

如果浏览器因为本地文件策略不播放视频，可以在当前目录启动任意静态文件服务后访问，例如：

```bash
python -m http.server 8080
```

然后打开：

```text
http://localhost:8080
```

## 给面试官查看

本仓库使用 GitHub Pages 发布。静态演示文件包括：

- `index.html`
- `demo-video.mp4`
- `zone-preview.png`

> 本演示使用公开测试录像和模拟数据，不连接真实摄像头、生产数据库或外部 API，也不包含任何密钥。

## 展示内容

- 药店后台数据看板
- 测试视频监控画面
- 药柜多边形识别分区
- 顾客与工作人员区分展示
- 区域停留触发广告的模拟流程
- 广播历史与当前播放文案
- 项目亮点说明
