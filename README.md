# 陇上青年·杭漂记 | 活动回顾

这是西西参与组织的 12 次活动回顾网页，包含足迹地图、时光长廊、精彩瞬间等模块。

## 📁 文件结构

```
activity-review/
├── 活动回顾.html      # 主页面
└── images/            # 图片资源
    ├── avatar.jpg     # 头像
    ├── 01.png ~ 12.png  # 活动照片
    └── 13.png         # 第 12 次活动海报
```

## 🚀 GitHub 部署方法

### 方法 1：GitHub Pages（推荐）

1. **创建仓库**
   ```bash
   # 在 GitHub 创建新仓库，例如：activity-review
   ```

2. **上传文件**
   ```bash
   cd activity-review
   git init
   git add .
   git commit -m "Initial commit - 活动回顾网页"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/activity-review.git
   git push -u origin main
   ```

3. **启用 GitHub Pages**
   - 进入仓库 Settings → Pages
   - Source 选择 `main` 分支
   - 点击 Save
   - 几分钟后访问：`https://YOUR_USERNAME.github.io/activity-review/`

### 方法 2：直接打开

直接双击 `活动回顾.html` 文件即可在浏览器中预览。

## 📊 数据统计

- **入群天数**: 120 天（2025-12-10 至 2026-04-09）
- **已完成活动**: 11 场
- **距离演唱会**: 9 天（2026-04-18）

## 🗺️ 活动足迹

| 区县 | 活动次数 |
|------|----------|
| 余杭区 | 5 次 |
| 西湖区 | 2 次 |
| 临安区 | 1 次 |
| 上城区 | 1 次 |
| 海宁市 | 1 次 |
| 长兴县 | 1 次 |
| 钱塘区 | 1 次 |

## 🎨 技术栈

- 高德地图 JS API v2.0
- 纯 HTML/CSS/JavaScript
- 响应式设计
- 暗黑主题 + 金色渐变

## 📝 注意事项

1. 地图需要联网才能加载（使用高德 API）
2. 照片路径使用相对路径 `images/xx.png`
3. 头像文件为 `images/avatar.jpg`
4. 第 12 次活动照片使用 `12.png`（场地照）

## 👤 关于

- **组织者**: 西西
- **群体**: 陇上青年（甘肃人在杭州）
- **时间跨度**: 2025-2026

---

**愿我们在异乡的路上，始终有彼此相伴 🌟**
