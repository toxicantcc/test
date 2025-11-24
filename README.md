<!--
 * @Author: heweidong 17521287703@163.com
 * @Date: 2025-11-24 11:39:57
 * @LastEditors: heweidong 17521287703@163.com
 * @LastEditTime: 2025-11-24 11:48:46
 * @FilePath: /test/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# test

## 点击测试页面

这是一个简单的HTML页面，包含一个"点击测试"按钮。

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