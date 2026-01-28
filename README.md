# 新年倒计时页面

这是一个美观的新年倒计时页面，使用纯HTML、CSS和JavaScript构建，无需任何外部依赖。

## 功能特性

- 实时倒计时显示距离下一个新年的时间
- 响应式设计，适配移动设备
- 美观的渐变背景和毛玻璃效果
- 自动计算下一年的1月1日作为目标日期
- 根据剩余时间显示不同的祝福语

## 部署到Cloudflare Pages

### 方法一：通过GitHub仓库（推荐）

1. 将此项目推送到GitHub仓库
2. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. 进入 "Pages" 服务
4. 点击 "Create a project" 
5. 选择您的GitHub账户并授权
6. 选择您刚刚创建的仓库
7. 在 "Build configuration" 部分：
   - Framework preset: 选择 "Static site"
   - Build command: 留空
   - Build output directory: `/` (根目录)
8. 点击 "Save and deploy"
9. Cloudflare会自动构建并部署您的网站

### 方法二：直接上传ZIP文件

1. 将项目文件打包成ZIP格式
2. 在Cloudflare Pages中选择 "Upload assets"
3. 上传ZIP文件
4. Cloudflare会自动部署

### 自定义域名

部署完成后，您可以：
- 使用Cloudflare提供的子域名（例如：yourname.pages.dev）
- 绑定自定义域名（需要在域名注册商处配置DNS记录）

## 技术细节

- HTML5
- CSS3（包括Flexbox和渐变效果）
- JavaScript（ES6+）
- 响应式设计
- 无外部依赖

## 自定义

您可以轻松修改样式：
- 更改颜色主题：修改CSS中的渐变色值
- 修改布局：调整.container的样式
- 添加更多动画效果：使用CSS transitions或JavaScript