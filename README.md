# UM-Blog

个人博客项目，前端使用Next.js，后端使用Rust的Axum框架，数据库使用MongoDB Atlas。

## 项目结构

- `/frontend` - Next.js前端项目
- `/backend` - Rust Axum后端API服务

## 技术栈

### 前端
- Next.js 14
- React
- TypeScript
- Tailwind CSS

### 后端
- Rust
- Axum框架
- MongoDB（通过Atlas云服务）

## 如何开始

### 前端开发
```bash
# 进入前端目录
cd frontend

# 安装依赖
npm install

# 启动开发服务器
npm run dev
```
前端服务会在 http://localhost:3000 启动

### 后端开发
```bash
# 进入后端目录
cd backend

# 编译并运行
cargo run
```
后端API服务会在 http://localhost:8080 启动

## API接口

- `GET /` - 健康检查
- `GET /api/posts` - 获取博客文章列表

## 项目规划

- [x] 前端基础框架
- [x] 后端基础框架
- [ ] MongoDB Atlas集成
- [ ] 博客CRUD功能
- [ ] 用户认证
- [ ] 评论系统
- [ ] SEO优化
- [ ] 部署到Vercel和其他平台 