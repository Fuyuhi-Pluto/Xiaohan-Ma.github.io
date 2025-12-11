# 学术个人网站框架

这是一个完整的、现代化的学术个人网站模板，专为博士生、博士后和研究人员设计，用于展示研究工作和申请postdoc职位。

## 📋 功能特点

- ✅ **专业设计**：现代、简洁的学术风格界面
- ✅ **完全响应式**：在所有设备上完美显示
- ✅ **易于定制**：清晰的代码结构，便于修改
- ✅ **SEO优化**：帮助提高搜索引擎排名
- ✅ **快速加载**：优化的性能和资源加载
- ✅ **无需编程**：只需替换内容，不需要编程知识

## 📁 文件结构

```
academic-website/
│
├── index.html              # 主页
├── research.html          # 研究页面
├── publications.html      # 出版物页面
├── cv.html               # 简历页面
├── contact.html          # 联系页面
├── README.md             # 本文件
│
├── css/
│   └── style.css         # 主样式文件
│
├── js/
│   └── main.js           # JavaScript交互脚本
│
├── images/               # 图片文件夹
│   ├── profile.jpg       # 个人照片（需要添加）
│   ├── project1.png      # 项目图片（需要添加）
│   ├── project2.png
│   ├── paper1-thumbnail.png
│   └── paper2-thumbnail.png
│
└── files/                # 文档文件夹
    └── CV.pdf           # 简历PDF（需要添加）
```

## 🚀 快速开始

### 第1步：替换个人信息

在每个HTML文件中，搜索并替换以下占位符：

- `[你的姓名]` → 你的真实姓名
- `[所属大学/研究所]` → 你的机构
- `[研究方向]` → 你的具体研究领域
- `your.email@university.edu` → 你的邮箱
- `[办公室地址]` → 你的办公地址

### 第2步：添加照片和文件

1. **个人照片**：将你的专业照片命名为 `profile.jpg`，放入 `images/` 文件夹
   - 推荐尺寸：800x800像素
   - 格式：JPG或PNG
   - 背景：干净、专业

2. **项目图片**：添加研究项目的示意图
   - `project1.png`, `project2.png` 等
   - 推荐尺寸：800x600像素

3. **论文缩略图**：为重要论文添加图示
   - `paper1-thumbnail.png`, `paper2-thumbnail.png`
   - 推荐尺寸：400x300像素

4. **简历PDF**：将最新简历保存为 `CV.pdf`，放入 `files/` 文件夹

### 第3步：填写内容

#### **首页 (index.html)**

1. 更新英雄区的个人介绍
2. 填写研究兴趣卡片（3个主要方向）
3. 添加最新动态/新闻
4. 展示2-3篇精选论文

#### **研究页面 (research.html)**

1. 撰写研究概述（3-5段）
2. 描述当前进行的研究项目
3. 列出已完成的项目
4. 更新研究方法和技能列表
5. 添加合作者信息

#### **出版物页面 (publications.html)**

1. 更新统计数据（论文数、引用数、H-index）
2. 按年份倒序添加所有论文
3. 提供PDF、DOI、代码等链接
4. 标记第一作者和通讯作者论文
5. 添加会议论文和演讲

#### **简历页面 (cv.html)**

1. 填写教育背景
2. 添加研究经历
3. 列出荣誉和奖励
4. 记录教学经历
5. 更新技能标签
6. 添加推荐人信息

#### **联系页面 (contact.html)**

1. 更新联系方式
2. 添加所有学术档案链接（Google Scholar、ORCID等）
3. 说明合作机会
4. 嵌入办公地点地图（可选）

### 第4步：自定义样式（可选）

如果想更改颜色方案，编辑 `css/style.css` 文件中的CSS变量：

```css
:root {
    --primary-color: #1a4d7a;      /* 主色调 */
    --accent-color: #d4a574;       /* 强调色 */
    --text-dark: #1a1a1a;          /* 文字颜色 */
    /* ... 其他颜色 */
}
```

## 🌐 部署方法

### 方法1：GitHub Pages（推荐 - 免费）

1. 在GitHub创建一个新仓库，命名为 `yourusername.github.io`
2. 上传所有文件到仓库
3. 在仓库设置中启用GitHub Pages
4. 你的网站将在 `https://yourusername.github.io` 上线

详细步骤：
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### 方法2：Netlify（免费 + 自定义域名）

1. 访问 [netlify.com](https://netlify.com)
2. 连接你的GitHub仓库或直接拖拽文件夹
3. 自动部署，获得免费域名
4. 可选：购买自定义域名并连接

### 方法3：学校服务器

大多数大学为教职工和学生提供免费网页空间：

1. 联系你的IT部门获取FTP或SSH访问权限
2. 上传所有文件到指定目录
3. 网站通常在 `www.university.edu/~yourusername` 可访问

## ✅ 上线前检查清单

- [ ] 所有 `[占位符]` 都已替换
- [ ] 添加了个人照片
- [ ] 上传了简历PDF
- [ ] 所有链接都能正常工作
- [ ] 邮箱地址正确无误
- [ ] 在移动设备上测试显示效果
- [ ] 检查拼写和语法
- [ ] 添加了Google Scholar、ORCID等学术档案链接
- [ ] 测试了所有按钮和交互功能

## 📱 在移动设备上测试

1. 在浏览器中打开网站
2. 按 F12 打开开发者工具
3. 点击设备模拟器图标
4. 测试不同设备尺寸的显示效果

## 🔧 常见问题

### Q: 如何更改导航栏顺序？
A: 编辑每个HTML文件的 `<nav>` 部分，调整 `<li>` 标签的顺序。

### Q: 如何添加新页面？
A: 复制现有HTML文件，修改内容，然后在导航栏添加链接。

### Q: 图片不显示怎么办？
A: 检查图片路径是否正确，文件名是否匹配，文件是否在 `images/` 文件夹中。

### Q: 如何嵌入Google地图？
A: 
1. 访问 [Google Maps](https://maps.google.com)
2. 搜索你的位置
3. 点击"分享" → "嵌入地图"
4. 复制iframe代码
5. 替换 `contact.html` 中的地图代码

### Q: 如何添加Google Analytics？
A: 在所有HTML文件的 `</head>` 标签前添加：

```html
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_TRACKING_ID');
</script>
```

## 🎨 设计灵感

本网站采用：
- **字体**：Crimson Pro（标题）+ IBM Plex Sans（正文）
- **配色**：海军蓝 + 暖金色 的专业学术配色
- **布局**：网格系统 + 卡片式设计
- **风格**：简洁、现代、专业

## 📈 SEO优化建议

1. **Meta标签**：每个页面都有描述和关键词
2. **图片Alt文本**：为所有图片添加描述
3. **内部链接**：页面之间相互链接
4. **定期更新**：经常添加新内容（论文、博客等）
5. **社交媒体**：在学术社交平台分享你的网站

## 🔒 隐私和安全

- 只展示公开的学术信息
- 不要包含敏感个人数据
- 使用学术邮箱而非私人邮箱
- 定期备份网站文件

## 📞 获取帮助

如果遇到技术问题：
1. 检查浏览器控制台的错误信息（F12）
2. 验证所有文件路径是否正确
3. 确保所有HTML标签正确闭合
4. 在StackOverflow搜索相关问题

## 📝 维护建议

- **每月更新**：添加新论文、新闻、研究进展
- **季度检查**：测试所有链接，更新简历
- **年度审查**：重新评估内容，更新设计

## 🌟 进阶功能（可选）

想要添加更多功能？考虑：

1. **博客系统**：使用Jekyll或Hugo
2. **评论功能**：集成Disqus
3. **搜索功能**：添加站内搜索
4. **多语言**：创建英文/中文版本
5. **暗黑模式**：添加主题切换

## 📚 推荐资源

- [Google Scholar](https://scholar.google.com) - 学术搜索
- [ORCID](https://orcid.org) - 研究人员ID
- [ResearchGate](https://researchgate.net) - 学术社交网络
- [GitHub](https://github.com) - 代码托管

## 🎓 针对Postdoc申请的建议

1. **突出独立研究能力**：展示你主导的项目
2. **强调技术技能**：详细列出实验和计算技能
3. **量化成果**：论文数量、引用次数、资助金额
4. **展示合作能力**：列出合作者和跨学科项目
5. **保持更新**：申请期间定期更新内容

## 📄 许可证

本模板可以自由使用、修改和分发。无需署名，但欢迎分享给其他学者！

---

**祝你申请顺利！如有问题，欢迎联系。**

最后更新：2024年12月
