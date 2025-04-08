# AI Portfolio - 炫酷科技感个人网站

这是一个具有强烈AI科技感设计的个人作品集网站，用于展示个人作品和简历。网站采用现代设计元素，结合AI科技感，并确保良好的用户体验。

## 特点

- **炫酷的AI科技感设计**：采用未来主义设计元素，包括故障效果、渐变、光晕和动态元素
- **响应式布局**：适配各种设备尺寸，从手机到桌面显示器
- **交互式元素**：自定义光标、滚动动画、技能进度条等
- **项目展示**：分类展示项目，支持筛选功能
- **技能展示**：直观展示技能水平
- **简历部分**：展示专业经历和教育背景
- **联系表单**：方便访客与你取得联系

## 技术栈

- HTML5
- CSS3 (Flexbox, Grid, 动画, 渐变)
- JavaScript (原生JS，无框架依赖)
- Font Awesome 图标
- Google Fonts (Orbitron, Roboto)

## 文件结构

```
ai_portfolio/
├── index.html          # 主HTML文件
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # JavaScript文件
└── images/             # 图像文件夹
    ├── profile-placeholder.jpg
    ├── about-placeholder.jpg
    ├── project1.jpg
    ├── project2.jpg
    ├── project3.jpg
    └── project4.jpg
```

## 使用指南

### 安装

1. 克隆或下载此仓库
2. 打开`index.html`文件在浏览器中查看网站

### 自定义

#### 个人信息

编辑`index.html`文件，替换以下内容：

- 姓名
- 职业描述
- 关于我部分
- 技能和熟练度
- 项目信息
- 简历内容
- 联系信息

#### 图像

替换`images`文件夹中的占位图像：

- `profile-placeholder.jpg` - 你的个人照片
- `about-placeholder.jpg` - 关于部分的图像
- `project1.jpg` - `project4.jpg` - 项目截图或相关图像

#### 颜色主题

在`css/style.css`文件中修改`:root`变量来更改颜色主题：

```css
:root {
    --primary-color: #00f7ff;
    --secondary-color: #6c63ff;
    --accent-color: #ff00aa;
    --dark-color: #0a0a0a;
    --light-color: #f5f5f5;
    /* 其他变量 */
}
```

## 浏览器兼容性

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 许可

MIT许可证 - 随意使用和修改

## 作者

你的名字

---

**注意**：这是一个静态网站模板，不包含后端功能。联系表单需要额外的后端服务才能正常工作。 
