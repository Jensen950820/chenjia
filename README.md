# 晨佳专属相册

每一次快门，都是重逢的证言 ✨

## 使用

直接双击 `index.html` 浏览器打开，无需服务器。

## 照片

```
images/
├── 20211226/        ← 用日期命名子文件夹
│   ├── 01.jpg
│   └── 02.jpg
├── 20220221/
└── ...
```

上传后在页面点 📝 编辑，把相册链接改为 `/images/20211226/`。

## 音乐

1. 去 [Pixabay Music](https://pixabay.com/music/) 下载 MP3
2. 放到 `music/` 文件夹
3. 点页面右下角 📝 编辑，找到 `MUSIC_URLS` 改为：
   ```
   ["/music/你的歌.mp3"]
   ```

## 功能

- 时间轴 + 可视化比例尺
- 距上次见面倒计时
- 暗色模式（点 🌙）
- 点击卡片弹窗浏览
- 天气/季节徽章
- 纪念海报生成
- 内置钢琴背景音
- 数据编辑/导入/导出

## 部署

GitHub Pages：推送到仓库 → Settings → Pages → 选 main 分支 → Save

## 在线链接

https://jensen950820.github.io/chenjia/
