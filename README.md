# Ride Tracker

骑行轨迹本地可视化工具。

## 使用方法

在浏览器中直接打开 `index.html` 即可使用（推荐 Chrome / Edge）。

## 功能

- 上传 GPX / KML / KMZ 轨迹文件
- 地图上叠加显示所有历史轨迹
- 骑行越频繁的路段颜色越深（热力图效果）
- 日历时间轴：选择截止日期，只显示该日期之前的轨迹
- 点击历史记录跳转到对应轨迹
- 所有数据存储在浏览器本地（IndexedDB），不涉及任何服务器

## 部署到 GitHub Pages

1. 将整个项目推送到 GitHub 仓库
2. 在仓库 Settings → Pages → Source，选择 `main` branch 和 `/ (root)` 文件夹
3. 等待部署完成后通过 `https://你的用户名.github.io/仓库名/` 访问
