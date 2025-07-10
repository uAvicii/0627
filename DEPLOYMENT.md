# 🚀 自动部署配置说明

## 部署状态
- **平台**: Vercel
- **生产环境**: https://0627-8sqgblfe8-uaviciis-projects.vercel.app
- **自动部署**: ✅ 已启用

## 自动部署流程

### 1. GitHub集成部署 (推荐)
Vercel已经与您的GitHub仓库集成，每当您推送代码到`main`分支时，Vercel会自动：
- 检测代码更改
- 构建项目
- 部署到生产环境
- 提供新的部署URL

### 2. 手动部署
如果需要手动部署，可以使用以下命令：
```bash
# 部署到生产环境
vercel --prod

# 部署到预览环境
vercel
```

### 3. GitHub Actions工作流
我们还配置了GitHub Actions工作流(`auto-deploy.yml`)，它会：
- 在每次推送时运行代码质量检查
- 提供部署状态通知
- 确保部署流程的可视化

## 部署触发条件
- ✅ 推送到`main`分支
- ✅ 合并Pull Request到`main`分支
- ✅ 直接在GitHub上编辑文件

## 部署历史
- 最新部署: 微信二维码弹窗功能
- 部署时间: 自动
- 部署状态: ✅ 成功

## 注意事项
1. 每次推送都会触发自动部署
2. 部署通常需要1-3分钟完成
3. 可以在Vercel仪表板查看部署日志
4. 如果部署失败，会收到邮件通知

## 快速部署命令
```bash
# 一键提交并部署
git add .
git commit -m "feat: 新功能描述"
git push origin main

# Vercel会自动检测并部署
```

## 环境变量
如果项目需要环境变量，可以在Vercel仪表板中配置：
1. 访问 https://vercel.com/dashboard
2. 选择项目
3. 进入Settings > Environment Variables
4. 添加所需的环境变量

---
🎉 **恭喜！您的博客现在支持自动部署了！** 