# MAS Chapter 1 翻页阅读器

一节一节学习的 HTML 翻页阅读器（基于 NotebookLM 精准翻译 + 个人总结）。

## 手机访问
直接打开 `index.html` 即可。推荐部署后用手机浏览器书签或添加到主屏幕。

## 如何部署（推荐 GitHub Pages）

### 最快方式（网页操作，5 分钟）
1. 去 GitHub 新建一个 **公开** 仓库，名字随便（例如 `mas-chapter1-reader`）
2. 把这个文件夹里的 `index.html` 上传到仓库根目录（网页界面可以直接拖拽上传）
3. 仓库设置 → Pages → Source 选 "Deploy from a branch" → Branch: `main` / `root`
4. 等 1-2 分钟，访问：  
   `https://你的用户名.github.io/mas-chapter1-reader/`

以后更新：直接修改 index.html 再上传覆盖，Pages 会自动更新。

### 用 Git 方式（推荐长期维护）
```bash
git init
git add .
git commit -m "init Chapter 1 flip reader"
git branch -M main
git remote add origin https://github.com/你的用户名/mas-chapter1-reader.git
git push -u origin main
```
然后按上面设置 Pages。

## 更新内容
以后每学完一节（比如 1.3），我就会帮你更新这个文件里对应页面的内容。你只需要重新上传 `index.html` 即可。

## 手机阅读提示
- 竖屏单手操作友好
- 左右按钮或点击顶部小节名翻页
- 原文/翻译卡片支持上下滑动
- 建议添加到手机主屏幕（浏览器菜单 → 添加到主屏幕）

## 离线使用
目前依赖 CDN（Tailwind + FontAwesome），需要网络。以后如果需要纯离线版可以告诉我，我可以把依赖内联。

学习愉快！
