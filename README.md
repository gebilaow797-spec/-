# 校园交友系统

一个现代化的校园社交平台，帮助在校大学生建立连接、扩展社交圈子。

## 功能特性

### 用户管理
- 注册与登录（邮箱/学号验证）
- 个人资料管理（头像、签名、兴趣标签）
- 隐私设置与安全控制

### 社交功能
- **发现功能**：基于兴趣和地理位置推荐用户
- **匹配系统**：智能匹配合适的交友对象
- **消息聊天**：实时一对一聊天和群组讨论
- **点赞与互动**：点赞、评论、分享用户主页

### 社群功能
- 兴趣小组
- 话题讨论
- 活动发起与报名
- 校内活动日历

### 安全机制
- 身份认证（校园邮箱验证）
- 内容审核
- 举报与封禁机制
- 隐私保护

## 技术栈

### 前端
- React 18
- TypeScript
- Vite
- TailwindCSS
- Redux Toolkit（状态管理）
- Socket.io（实时通信）

### 后端
- Node.js + Express
- TypeScript
- MongoDB（用户数据）
- Redis（缓存与实时消息）
- JWT（身份验证）
- Socket.io（WebSocket）

### DevOps
- Docker
- Docker Compose
- GitHub Actions（CI/CD）

## 项目结构

```
campus-dating-system/
├── frontend/                 # React前端应用
├── backend/                  # Node.js后端API
├── shared/                   # 共享类型和工具
├── docker-compose.yml        # Docker编排文件
└── README.md
```

## 快速开始

### 前置要求
- Node.js >= 16
- MongoDB
- Redis
- Docker（可选）

### 使用Docker启动

```bash
docker-compose up -d
```

### 本地开发

#### 后端
```bash
cd backend
npm install
npm run dev
```

#### 前端
```bash
cd frontend
npm install
npm run dev
```

## API文档

详见 `backend/API.md`

## 贡献指南

欢迎提交Issue和Pull Request！

## 许可证

MIT
