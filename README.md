# test

## 勇士点击测试页面

这是一个简单的HTML页面，包含一个"勇士点击测试"按钮。

### 部署到 GitHub Pages

#### 方法一：使用 GitHub Actions（推荐）

1. 推送代码到 GitHub：
   ```bash
   git push origin main
   ```

2. 在 GitHub 仓库设置中启用 Pages：
   - 进入仓库 Settings → Pages
   - Source 选择 "GitHub Actions"
   - 保存后，GitHub Actions 会自动部署

#### 方法二：使用传统方式

1. 推送代码到 GitHub：
   ```bash
   git push origin main
   ```

2. 在 GitHub 仓库设置中启用 Pages：
   - 进入仓库 Settings → Pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main"，文件夹选择 "/ (root)"
   - 点击 Save

部署完成后，页面将在 `https://toxicantcc.github.io/test/` 可访问。