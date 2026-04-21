# GM 全服邮件配置中台

> 高保真交互原型 | 米哈游/科幻基建风运营后台

## 在线部署指南

### 方案一：Netlify Drop（最快，无需注册）

1. 打开 https://app.netlify.com/drop
2. 将本文件夹内的 `index.html` 直接**拖拽**到网页中
3. 立刻获得一个 `xxx.netlify.app` 的在线网址

### 方案二：GitHub Pages（推荐，长期稳定）

1. 在 GitHub 新建一个仓库，名称随意（如 `gm-mail-platform`）
2. 把本文件夹内的 `index.html` 上传到仓库根目录
3. 进入仓库 **Settings → Pages**
4. Source 选择 **Deploy from a branch**，分支选 `main`，文件夹选 `/ (root)`
5. 保存后等待 1 分钟，即可通过 `https://你的用户名.github.io/仓库名/` 访问

### 方案三：Vercel（国内访问较快）

1. 打开 https://vercel.com/new
2. 导入刚才创建的 GitHub 仓库
3. 直接 Deploy，无需任何配置

## 技术栈

- React 18 (Production)
- Tailwind CSS CDN
- Framer Motion
- 内联 Lucide SVG 图标

## 本地预览

直接在浏览器中打开 `index.html` 即可。
