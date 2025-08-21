# AI-Agent 开发专家知识库

## 项目简介

AI-Agent 是一个专业的 AI 开发专家知识库项目，汇集了多个领域的开发专家经验和最佳实践。本项目旨在为开发者提供全面、实用的技术指导和开发规范，涵盖前端、后端、机器人开发等多个技术栈。

## 功能特性

### 🚀 多技术栈覆盖

- **Node.js 后端开发**：企业级后端应用开发指南，涵盖 Express、Koa、NestJS 等框架
- **Vue 前端开发**：现代 Vue 3 技术栈最佳实践，包含 TypeScript、Vite、Element Plus
- **前端开发通用指南**：跨框架前端开发规范，支持 React、Vue、Angular 等主流框架
- **前端代码质量审查**：专业的代码质量审查体系，采用 6A 工作流程
- **Telegram Bot 开发**：专业机器人应用开发经验，基于 Node.js 生态系统

### 📚 专业知识体系

- **完整技术栈指南**：从基础语法到高级架构的全面覆盖
- **6A 工作流程**：标准化的开发和审查流程（Analysis、Architecture、Algorithm、Automation、Assessment、Adjustment）
- **企业级最佳实践**：基于真实项目经验的架构设计和开发规范
- **代码质量保障**：涵盖代码规范、性能优化、安全性、可维护性四大维度
- **现代化工具链**：集成 ESLint、Prettier、Docker、CI/CD 等现代开发工具

### 🛠️ 实用工具集合

- **项目模板和脚手架**：快速启动各类项目的标准化模板
- **开发规范指南**：详细的代码风格和开发流程规范
- **工具链集成**：ESLint、Prettier、Jest、Docker、PM2 等工具的最佳配置
- **性能监控方案**：Prometheus、Grafana、Winston 等监控和日志工具
- **部署运维指南**：Docker 容器化、Kubernetes、CI/CD 流水线配置

## 项目结构

```
AI-agent/
├── .gitignore                   # Git 忽略文件配置
├── .obsidian/                   # Obsidian 配置文件
│   ├── app.json
│   ├── appearance.json
│   ├── core-plugins.json
│   └── graph.json
├── README.md                    # 项目说明文档
├── backend/                     # 后端开发专家指南
│   └── Node后端开发专家.md
├── docs/                        # 项目文档目录
│   └── 前端代码质量审查专家使用指南.md
├── frontend/                    # 前端开发专家指南
│   ├── Vue 前端开发专家.md
│   ├── 前端代码质量审查专家.md
│   └── 前端开发专家.md
└── tgbot/                       # Telegram Bot 开发指南
    ├── TGBot 开发专家.md
    └── TGBot 开发专家精简版.md
```

## 安装步骤

### 环境要求

- **Git**: 2.0+ 版本控制系统
- **编辑器**: 支持 Markdown 的编辑器
  - 推荐：Obsidian（知识图谱功能）
  - 备选：VS Code、Typora、Mark Text
- **Node.js**: 16.0+ （如需运行示例代码）
- **操作系统**: macOS、Windows、Linux 均支持

### 克隆项目

```bash
# 克隆仓库
git clone https://github.com/JackEngineer/AI-Agent.git

# 进入项目目录
cd AI-Agent
```

### 配置开发环境

#### 使用 Obsidian（推荐）

1. 下载并安装 [Obsidian](https://obsidian.md/)
2. 打开 Obsidian，选择「打开文件夹作为仓库」
3. 选择克隆的 AI-Agent 目录
4. Obsidian 会自动加载 `.obsidian/` 配置文件
5. 开始浏览和编辑知识库，享受知识图谱功能

#### 使用 VS Code

1. 安装推荐插件：
   - Markdown All in One
   - Markdown Preview Enhanced
   - GitLens
2. 打开项目文件夹
3. 使用 `Ctrl+Shift+V` 预览 Markdown 文件

#### 项目初始化（可选）

如果需要运行示例代码或开发工具：

```bash
# 安装 Node.js 依赖（如果有 package.json）
npm install

# 或使用 yarn
yarn install
```

## 使用说明

### 📖 阅读指南

1. **选择技术栈**：根据你的需求选择对应的专家指南
   - 后端开发：查看 `backend/Node后端开发专家.md`
   - Vue 前端开发：查看 `frontend/Vue 前端开发专家.md`
   - 通用前端开发：查看 `frontend/前端开发专家.md`
   - 代码质量审查：查看 `frontend/前端代码质量审查专家.md`
   - Bot 开发：查看 `tgbot/TGBot 开发专家.md`
   - 使用指南：查看 `docs/` 目录下的详细文档

2. **学习路径**：每个指南都包含完整的学习路径
   - 技术栈介绍
   - 开发规范
   - 最佳实践
   - 实战案例

3. **实践应用**：将指南中的规范和实践应用到你的项目中

### 🔍 快速查找

- 使用 Obsidian 的全文搜索功能快速定位内容
- 利用标签和链接功能建立知识关联
- 通过图谱视图查看知识结构

### 📝 个人定制

- 可以根据个人需求修改和扩展内容
- 添加个人笔记和实践经验
- 建立个人的知识管理体系

## 技术栈详情

### Node.js 后端开发

- **核心技术**：Node.js、TypeScript、Express、Koa、NestJS、Fastify
- **数据库技术**：PostgreSQL、MongoDB、Redis、Elasticsearch
- **ORM/ODM**：Prisma、TypeORM、Sequelize、Mongoose
- **API 设计**：RESTful API、GraphQL、OpenAPI/Swagger
- **身份认证**：JWT、OAuth 2.0、Passport.js、RBAC
- **测试框架**：Jest、Mocha、Supertest
- **部署运维**：Docker、Kubernetes、PM2、Nginx、CI/CD
- **监控日志**：Winston、Pino、Prometheus、Grafana

### Vue 前端开发

- **核心技术**：Vue 3、Composition API、TypeScript、Vite
- **状态管理**：Pinia、持久化、模块化设计
- **UI 框架**：Element Plus、主题定制、表单验证
- **路由管理**：Vue Router、导航守卫、懒加载
- **HTTP 客户端**：Axios、拦截器、错误处理
- **国际化**：Vue I18n、多语言切换
- **样式处理**：SCSS/Less、变量管理、混入
- **代码质量**：ESLint、Stylelint、代码规范

### Telegram Bot 开发

- **核心框架**：Telegraf.js、node-telegram-bot-api、Grammy
- **开发语言**：Node.js、TypeScript、现代 JavaScript
- **数据库技术**：MongoDB + Mongoose、PostgreSQL + Prisma/TypeORM、Redis
- **架构模式**：模块化架构、中间件模式、事件驱动架构
- **部署运维**：Docker 容器化、PM2 进程管理、Nginx 反向代理
- **云服务部署**：AWS、阿里云、腾讯云
- **CI/CD**：GitHub Actions、GitLab CI 自动化部署
- **错误处理**：全局异常捕获、优雅降级机制

## 贡献指南

我们欢迎所有形式的贡献！无论是内容完善、错误修正还是新增专家指南。

### 🤝 如何贡献

1. **Fork 项目**

   ```bash
   # Fork 本仓库到你的 GitHub 账户
   # 然后克隆你的 Fork
   git clone https://github.com/你的用户名/AI-Agent.git
   ```

2. **创建分支**

   ```bash
   # 创建新的功能分支
   git checkout -b feature/新功能名称
   # 或者创建修复分支
   git checkout -b fix/修复内容
   ```

3. **提交更改**

   ```bash
   # 添加更改的文件
   git add .
   
   # 提交更改（使用中文提交信息）
   git commit -m "添加：新增 React 开发专家指南"
   # 或
   git commit -m "修复：更正 Node.js 配置示例"
   ```

4. **推送分支**

   ```bash
   git push origin feature/新功能名称
   ```

5. **创建 Pull Request**
   - 在 GitHub 上创建 Pull Request
   - 详细描述你的更改内容
   - 等待代码审查和合并

### 📋 贡献规范

- **内容质量**：确保内容准确、实用、有价值
- **格式规范**：遵循现有的 Markdown 格式和结构
- **中文编写**：所有内容使用中文编写
- **代码示例**：提供清晰、可运行的代码示例
- **更新及时**：保持技术内容的时效性

### 🎯 贡献方向

- **新增专家指南**：React、Angular、Python、Java、Go、Rust 等技术栈
- **完善现有内容**：补充实战案例、最佳实践、性能优化方案
- **扩展文档体系**：添加更多使用指南、配置示例、故障排查手册
- **工具链集成**：开发自动化脚本、配置模板、项目脚手架
- **质量保障**：完善代码审查标准、测试用例、CI/CD 模板
- **社区建设**：建立问题反馈机制、经验分享平台

### 前端代码质量审查

- **审查体系**：采用 6A 工作流程（Assess、Analyze、Advise、Act、Audit、Adjust）
- **审查维度**：代码规范、性能优化、安全性、可维护性四大维度
- **问题分级**：Critical、Major、Minor 三级问题分类管理
- **工具集成**：ESLint、Prettier、SonarQube、Lighthouse 等静态分析工具
- **报告生成**：结构化审查报告和改进计划
- **持续改进**：长期质量监控和优化建议

### 通用前端开发

- **多框架支持**：React、Vue、Angular 等主流前端框架
- **现代工具链**：Webpack、Vite、Rollup、Parcel 构建工具
- **测试框架**：Jest、Vitest、Cypress、Testing Library
- **代码质量**：ESLint、Prettier、Husky、lint-staged
- **性能优化**：代码分割、懒加载、缓存策略
- **工程化实践**：模块化、组件化、自动化部署

## 版本历史

- **v2.0.0** (2025-01-XX)
  - 重构项目结构，按技术栈分类组织文档
  - 新增前端代码质量审查专家指南
  - 新增通用前端开发专家指南
  - 完善 6A 工作流程体系
  - 扩展技术栈覆盖范围
  - 新增 docs 文档目录

- **v1.0.0** (2025-08-19)
  - 初始版本发布
  - 包含 Node.js、Vue、TGBot 开发专家指南
  - 建立基础项目结构

## 许可证

本项目采用 MIT 许可证。详情请查看 [LICENSE](LICENSE) 文件。

## 联系方式

- **项目维护者**：JackEngineer
- **GitHub**：[https://github.com/JackEngineer](https://github.com/JackEngineer)
- **项目地址**：[https://github.com/JackEngineer/AI-Agent](https://github.com/JackEngineer/AI-Agent)

## 致谢

感谢所有为本项目贡献内容和建议的开发者们！你们的参与让这个知识库变得更加完善和有价值。

---

**⭐ 如果这个项目对你有帮助，请给我们一个 Star！**
