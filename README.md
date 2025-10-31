# 李亚林 - 个人简历

这是我的在线简历，使用 GitHub Pages 托管。

## 在线访问

访问地址：`https://neuneed.github.io/resume/`（部署后可用）

## 本地预览

直接在浏览器中打开 `index.html` 文件即可预览简历。

## 技术栈

- HTML5
- CSS3
- Pico CSS Framework
- Google Fonts (Inter)

## 功能特性

- ✅ A4 纸张大小布局（210mm × 297mm）
- ✅ 响应式设计
- ✅ 打印优化（支持直接打印或导出 PDF）
- ✅ 现代化 UI 设计
- ✅ 可点击的联系方式（电话、邮箱、GitHub）

## GitHub Pages 部署步骤

### 1. 创建 GitHub 仓库

```bash
# 在当前目录初始化 git 仓库
git init

# 添加所有文件
git add .

# 提交
git commit -m "Initial commit: Add resume"

# 在 GitHub 上创建一个名为 resume 的新仓库
# 然后关联远程仓库
git remote add origin https://github.com/neuneed/resume.git

# 推送到 GitHub
git branch -M main
git push -u origin main
```

### 2. 启用 GitHub Pages

1. 访问仓库设置：`https://github.com/neuneed/resume/settings/pages`
2. 在 "Source" 下拉菜单中选择 `main` 分支
3. 点击 "Save"
4. 等待几分钟后，你的简历将发布到 `https://neuneed.github.io/resume/`

### 3. 更新简历

每次修改后：

```bash
git add .
git commit -m "Update resume"
git push
```

GitHub Pages 会自动更新网站内容。

## 打印或导出 PDF

1. 在浏览器中打开简历页面
2. 按 `Ctrl+P` (Windows) 或 `Cmd+P` (Mac)
3. 选择 "保存为 PDF" 或直接打印
4. 确保页面设置为 A4 纸张大小

## 自定义

修改 `index.html` 文件即可更新简历内容：

- 个人信息：修改左侧栏的联系方式
- 技能：更新技能列表
- 工作经验：添加或修改经验条目
- 教育背景：更新教育信息

## 许可

个人简历，仅供参考。

---

**李亚林 (Roland Lee)**  
高级软件开发工程师  
📧 neuneed@gmail.com  
🔗 https://github.com/neuneed

