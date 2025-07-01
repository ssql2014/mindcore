# MindCore项目交接文档

## 项目概述
- **项目名称**：MindCore机器人大脑智能芯片商业计划书
- **创建日期**：2025-01-01
- **项目目录**：`/Users/qlss/Documents/mindcore`

## GitHub仓库信息
- **仓库地址**：https://github.com/ssql2014/mindcore
- **仓库状态**：Public（公开）
- **GitHub Pages**：已启用
- **主分支**：main

## 文件清单

### 1. 演示文稿文件
- **mindcore-robotics-bp-1.html**
  - 描述：机器人大脑智能芯片商业计划书 V2.0（演示文稿版本1）
  - 访问链接：https://ssql2014.github.io/mindcore/mindcore-robotics-bp-1.html
  - 特点：深色主题，12页幻灯片，3D效果

- **mindcore-robotics-bp-2.html**
  - 描述：MindCore机器人大脑智能芯片（演示文稿版本2）
  - 访问链接：https://ssql2014.github.io/mindcore/mindcore-robotics-bp-2.html
  - 特点：简洁设计，12页幻灯片

### 2. 文档文件
- **robot-chip-bp-v2.md**
  - 描述：商业计划书完整Markdown版本
  - 内容：包含所有商业计划详细信息

- **robot-hardware-research.md**
  - 描述：机器人硬件研究文档
  - 内容：硬件相关研究资料

## 已实现功能

### 1. 密码保护
- **密码**：`mindcore2024`
- **实现方式**：前端JavaScript验证
- **特点**：
  - 输入一次密码后，会话期间无需重复输入
  - 支持Enter键提交
  - 显示错误提示

### 2. 移动端适配
- **响应式设计**：完美适配iPhone和其他移动设备
- **触摸手势**：支持左右滑动切换幻灯片
- **优化内容**：
  - 字体大小自适应
  - 表格可横向滚动
  - 布局自动调整

### 3. 团队信息更新
- **核心团队**：CEO、CTO、首席架构师、软件VP
- **顾问委员会**（新增）：
  - 学术顾问：中科院计算所资深研究员
  - 产业顾问：机器人行业资深专家
  - 电机控制顾问：曾任罗克韦尔与埃斯顿自动化高管

## 常用命令

### 基础操作
```bash
# 进入项目目录
cd /Users/qlss/Documents/mindcore

# 查看文件列表
ls

# 查看Git状态
git status
```

### 修改密码
1. 编辑HTML文件，找到以下代码行：
```javascript
const correctPassword = 'mindcore2024'; // 您可以修改这个密码
```
2. 将 `mindcore2024` 改为新密码

### 提交更改
```bash
# 添加所有更改
git add -A

# 提交更改
git commit -m "更新说明"

# 推送到GitHub
git push
```

### 本地预览
```bash
# 使用Python启动本地服务器
python3 -m http.server 8000

# 然后在浏览器访问
# http://localhost:8000/mindcore-robotics-bp-1.html
# http://localhost:8000/mindcore-robotics-bp-2.html
```

## 注意事项

1. **密码安全性**：当前使用的是前端密码保护，源代码中可以看到密码。这只能提供基础的访问控制。

2. **更新延迟**：推送到GitHub后，GitHub Pages可能需要几分钟才能更新。

3. **浏览器兼容性**：已测试Chrome、Safari、Firefox，移动端完美支持。

4. **仓库可见性**：当前仓库是公开的，任何人都可以查看源代码。如需更高安全性，考虑：
   - 升级到GitHub Pro使用私有仓库的Pages功能
   - 使用其他部署平台（Vercel、Netlify等）

## 项目结构
```
/Users/qlss/Documents/mindcore/
├── mindcore-robotics-bp-1.html    # 演示文稿1
├── mindcore-robotics-bp-2.html    # 演示文稿2
├── robot-chip-bp-v2.md            # 商业计划书
├── robot-hardware-research.md     # 硬件研究文档
└── PROJECT_HANDOVER.md           # 本交接文档
```

## 联系信息
如需技术支持，可以：
1. 查看GitHub仓库的提交历史
2. 使用Claude或其他AI助手继续开发
3. 参考本文档进行操作

---
最后更新：2025-01-01