# BlogBurst-API
BlogBurst-API
二、BlogBurst-API README
markdown
Copy
Edit
# 🚀 BlogBurst-API

**BlogBurst-API** 是一个极速、灵活且可扩展的博客后端服务，提供文章管理、用户认证、评论互动、标签分类等核心功能。

---

## 🎉 核心特性
- **RESTful API** | 清晰规范的接口设计  
- **高性能** | 使用 Spring Boot + MyBatis-Plus + Redis 缓存  
- **安全认证** | JWT + Spring Security，轻松集成第三方 OAuth  
- **模块化** | 按功能拆分包结构，开闭原则友好扩展  
- **文档自动化** | Swagger + Knife4j，一键查看、调试接口  

---

## 🛠 技术栈
- **框架**：Spring Boot 3.x  
- **持久层**：MyBatis-Plus  
- **缓存**：Redis  
- **认证**：Spring Security + JWT  
- **文档**：Swagger3 + Knife4j  
- **数据库**：MySQL  

---

## 🚀 快速开始

1. 克隆仓库
   ```bash
   git clone https://github.com/你的用户名/BlogBurst-API.git
   cd BlogBurst-API
配置数据库（src/main/resources/application.yml）

yaml
Copy
Edit
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/blogburst
    username: root
    password: your_password
redis:
  host: localhost
  port: 6379
jwt:
  secret: your_jwt_secret
运行项目

bash
Copy
Edit
mvn clean spring-boot:run
打开文档
浏览器访问：http://localhost:8080/doc.html

📦 模块说明
controller — API 接口层

service — 业务逻辑层

mapper — MyBatis 映射文件

config — 全局配置、拦截器、跨域等

dto — 请求/响应对象

entity — 数据库实体类

🤝 贡献指南
Fork 本仓库

新建分支：git checkout -b feature/你的功能

提交代码：git commit -m 'Add some feature'

推送分支：git push origin feature/你的功能

打开 PR

📝 许可证
本项目遵循 MIT License。

小提示：
每天一杯咖啡，写出高质量日志！☕

yaml
Copy
Edit

---

## 三、`BlogBurst-Web` README

```markdown
# 🌟 BlogBurst-Web

**BlogBurst-Web** 是 BlogBurst 系列的前端展示项目，采用 Vue 3 + Vite + TailwindCSS，打造流畅、简洁、响应式的博客阅读与创作体验。

---

## 🎨 功能亮点
- **响应式布局** | 手机/平板/PC 全覆盖  
- **Markdown 编辑** | 实时渲染，高亮预览  
- **文章分类与搜索** | 快速定位感兴趣内容  
- **评论互动** | 支持回复、点赞、表情包  
- **夜间模式** | 保护眼睛，24h 无压力阅读  

---

## 🛠 技术栈
- **框架**：Vue 3 + Composition API  
- **打包**：Vite  
- **样式**：TailwindCSS  
- **状态管理**：Pinia  
- **路由**：Vue Router  
- **HTTP**：Axios  

---

## 🚀 快速开始

1. 克隆仓库
   ```bash
   git clone https://github.com/你的用户名/BlogBurst-Web.git
   cd BlogBurst-Web
安装依赖

bash
Copy
Edit
npm install
配置后端地址（src/config.js）

js
Copy
Edit
export const API_BASE = 'http://localhost:8080';
启动开发

bash
Copy
Edit
npm run dev
打包发布

bash
Copy
Edit
npm run build
📁 目录结构
csharp
Copy
Edit
BlogBurst-Web/
├─ public/      # 静态资源
├─ src/
│  ├─ assets/   # 图片/字体
│  ├─ components/ # 复用组件
│  ├─ views/    # 页面视图
│  ├─ router/   # 路由配置
│  ├─ store/    # Pinia 状态管理
│  └─ App.vue、main.js
└─ vite.config.js
🤝 贡献指南
Fork 并 Clone

新建分支：git checkout -b feature/your-feature

提交并推送：git push origin feature/your-feature

提交 PR

❤️ 致谢
感谢所有为开源做贡献的小伙伴，一起让博客更精彩！

Tip：Ctrl+K 快速聚焦搜索，体验无缝阅读！🔍

yaml
Copy
Edit

---

这样，**BlogBurst-API** 与 **BlogBurst-Web** 两个仓库名统一而又鲜明，README 既通俗又活泼，能迅速抓住访客眼球。按照上述示例拷贝、填充自己的信息就可直接开箱即用！如果需要进一步补充或定制化，随时告诉我！







