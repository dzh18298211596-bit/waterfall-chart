# 降本单车瀑布图分析系统

📊 可交互式数据编辑与可视化平台

## 在线访问

部署后访问：`https://你的用户名.github.io/waterfall-chart/`

## 功能特点

✅ 动态瀑布图（左上到右下阶梯下降）
✅ 横坐标轴为0
✅ 自定义颜色选择
✅ 实时数据编辑
✅ 可修改图表标题
✅ 项目顺序调整
✅ 导出PNG图片
✅ 响应式设计

## 快速部署

### 1. 创建GitHub仓库
在GitHub创建新仓库（Public），名称如：`waterfall-chart`

### 2. 推送代码
```bash
cd C:\Users\dingzhonghua\waterfall-chart-github
git remote add origin https://github.com/你的用户名/waterfall-chart.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

### 3. 启用GitHub Pages
- 进入仓库 Settings → Pages
- Source 选择 "main" 分支
- 保存后等待1-2分钟

### 4. 在飞书中使用
直接分享链接即可，飞书会自动生成预览卡片

## 使用说明

- **编辑数据**：直接修改项目名称、数值
- **选择颜色**：点击彩色方块自定义颜色
- **调整顺序**：使用↑↓按钮
- **导出图片**：点击"💾 导出图表为图片"

## 技术栈

- 纯HTML + Canvas
- 无需后端
- 无外部依赖

## 许可证

MIT License
