# 医疗供应链管理系统

## 项目简介

这是一个基于Web的医疗供应链管理系统，主要用于管理和优化医疗机构的药物供应链流程。系统提供了全面的药物管理、库存跟踪和供应链可视化功能。

## 功能特点

- **仓储管理**：实现药品库存的实时监控和管理
- **供应链追踪**：提供完整的供应链可视化和追踪功能
- **数据分析**：支持供应链数据的分析和报表生成
- **临床试验管理**：支持临床试验过程中的药物管理
- **响应式设计**：支持多端设备访问

## 技术栈

- HTML5/CSS3
- JavaScript/jQuery
- Swiper.js - 轮播图组件
- AOS.js - 滚动动画效果
- Layer.js - 弹层组件

## 目录结构

```
├── images/          # 图片资源目录
├── styles/          # CSS样式文件
│   ├── common.css   # 公共样式
│   ├── index.css    # 主页样式
│   └── ...         # 其他样式文件
├── index-new.html   # 主页面
└── README.md       # 项目说明文档
```

## 运行环境要求

- 现代浏览器（Chrome、Firefox、Safari、Edge等）
- Python 3.x（用于本地开发服务器）

## 快速开始

1. 克隆项目到本地：
```bash
git clone [项目地址]
```

2. 进入项目目录：
```bash
cd web2
```

3. 启动本地服务器：
```bash
python3 -m http.server 8080
```

4. 在浏览器中访问：
```
http://localhost:8080/index-new.html
```

## 开发说明

- 页面样式使用响应式设计，支持移动端和桌面端
- 使用AOS库实现页面滚动动画效果
- 图片资源存放在images目录下
- 样式文件按模块分类存放在styles目录下

## 贡献指南

1. Fork 本仓库
2. 创建新的功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 许可证

[MIT License](LICENSE)