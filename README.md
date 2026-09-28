# 众夏智能工作台 · AI Workbench Demo

一个纯静态的单页 AI 工作台演示界面，可直接部署到 GitHub Pages。

## 在线预览

启用 GitHub Pages 后访问：

```
https://dinoxxx.github.io/zhongxia-ai-workbench/
```

仓库地址：https://github.com/dinoxxx/zhongxia-ai-workbench

## 技术说明

- 单个 `index.html`，无构建步骤、无依赖安装
- 图表能力来自 CDN 引入的 [Chart.js 4.4.1](https://www.chartjs.org/)
- 含 `.nojekyll`，跳过 Jekyll 处理，静态文件按原样发布

## 本地预览

```bash
# 任选一种
python -m http.server 8000
npx serve .
```

然后打开 http://localhost:8000

## 部署方式

仓库 Settings → Pages → Source 选择 `Deploy from a branch`，分支 `main`、目录 `/ (root)`，保存后等待 1~2 分钟即可。
