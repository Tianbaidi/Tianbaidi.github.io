# Zhan Yang · 个人主页

从头编写的静态个人主页。英文双栏、浅色纸面与普通衬线排版；桌面左侧为个人信息，右侧为经历、项目和文章，手机端纵向排列，不依赖 Hamilton、Jekyll、JavaScript 或其他网站模板。

## 本地查看

```sh
python3 -m http.server 4173
```

打开 http://localhost:4173 。页面由 GitHub Pages 从 `master` 根目录发布，`.nojekyll` 禁用 Jekyll 处理。

## 编辑

- `index.html`：个人介绍、文章索引、经历、项目、社交链接。
- `assets/style.css`：响应式排版与打印样式。
- `assets/images/avatar.png`：用户提供的插画。当前发布内容不含个人照片。
- `assets/icons/`：本地托管的平台图标。

文章列表是人工维护的索引，不会自动同步 Rinspace。新增文章时更新标题、日期与链接。

## 图标来源（2026-10-21 获取）

- GitHub、Bilibili、知乎、微信：从 Simple Icons 官方 npm 包重新下载的 SVG（https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/），CC0，品牌商标属于各自所有者。
- Rinspace：https://rinspace.com/assets/brand/rinspace-mark-128.png 。现站实际提供的是 PNG，`rinspace.svg` 将该原图嵌入 SVG 容器，保留官方图形；并非伪造的纯矢量版本。
- 字标 `monogram.svg` 由本项目编写。
- Rinspace 当前个人主页：https://rinspace.com/@satori 。文章链接取自该主页公开文章列表。
- 其他社交地址沿用此前主页已公开的链接；微信入口指向一篇公开文章，不宣称它是账号主页。

此前 Hamilton 主题的代码、示例文章与照片已从当前版本移除，旧版本仍可通过 Git 历史找回。`LICENSE.txt` 保留原主题历史版权说明；插画和品牌标记不因此获得许可。GitHub 的 fork 关联是仓库级元数据，与页面是否继续使用模板无关。
