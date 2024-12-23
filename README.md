
##  项目简介
-  前端技术栈： [Vue3.5](https://cn.vuejs.org/)、[Ant Design Vue](https://www.antdv.com/)、[UnoCSS](https://unocss.dev/)、[Pinia](https://pinia.vuejs.org/)

-  后端技术栈： [Nest.js](https://nestjs.com/)、[PostgreSQL](https://www.postgresql.org/)、[Prisma](https://prisma.yoga/)

-  用户名：**Admin**，密码：**abc123456**



##  系统功能设计


##  环境和依赖
> 推荐本项目使用 [pnpm](https://github.com/pnpm/pnpm/) 包管理工具
- [Git](https://git-scm.com/) (你需要git来克隆和管理项目版本)
- [Node.js](https://nodejs.org/) (Node.js 版本要求 >= 18.12.0，推荐 18.19.0 或更高)
- [Pnpm](https://github.com/pnpm/pnpm/) (>= 8.7.0，推荐最新版本)
- [PostgreSQL](https://www.postgresql.org/) (推荐最新版本)

##  项目运行
1. 安装 [PostgreSQL](https://www.postgresql.org/) 数据库，并导入 `/postgreSQL` 中的文件，修改 `/server/env` 文件中的数据库配置，这一步要保证成功，不然后端服务起不来
```powershell
DATABASE_URL="postgresql://postgres:123456@localhost:5432/vue3-admin?schema=public"
```

2. 拉取项目代码
```powershell
git clone https://github.com/baiwumm/vue3-admin.git
cd vue3-admin
// 进入前端
cd web
// 进入后端
cd server
```

3. 安装依赖
```powershell
npm install -g pnpm
pnpm install
```

4. 开发模式运行
```powershell
// 前端启动
pnpm dev
// 后端启动：开发模式
pnpm start:dev
```

5. 编译项目
```powershell
pnpm build
```
