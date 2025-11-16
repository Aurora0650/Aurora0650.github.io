# 羽毛球俱乐部网站

这是一个为羽毛球爱好者提供的静态网站，包含以下功能模块：
- 首页
- 规则介绍
- 装备展示
- 赛事信息
- 技巧指导
- 管理员后台

## 服务器访问问题排查

### 1. 本地服务器启动

如果你在本地服务器上无法访问网站，可以尝试以下方法：

#### 方法一：使用Python 3
```bash
python3 -m http.server 8000
```

#### 方法二：使用Node.js的http-server
```bash
npm install -g http-server
http-server -p 8000
```

#### 方法三：使用PHP内置服务器
```bash
php -S localhost:8000
```

### 2. 页面无法加载

- 确保所有HTML文件都在根目录下
- 检查文件路径是否正确
- 确保所有外部资源（如CDN）都能正常访问

### 3. 管理员登录问题

- 确保用户名和密码正确
- 清除浏览器缓存和localStorage
- 检查浏览器控制台是否有JavaScript错误

### 4. GitHub Pages部署

- 确保仓库设置正确
- 检查分支和路径设置
- 等待几分钟让GitHub Pages更新

## 文件结构

```
├── index.html      # 首页
├── rules.html      # 规则介绍
├── equipment.html  # 装备展示
├── events.html     # 赛事信息
├── techniques.html # 技巧指导
├── admin.html      # 管理员后台
└── README.md       # 说明文档
```
