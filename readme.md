# sqlite + prisma

安装 vscode 插件

编辑器左边会多出一个 sqlite explorer 按钮，可以快速查看数据库内容

安装 初始化

```sh
npx prisma init --datasource-provider sqlite
```

Next steps:

1. Set the DATABASE_URL in the .env file to point to your existing database. If your database has no tables yet, read https://pris.ly/d/getting-started
2. Run prisma db pull to turn your database schema into a Prisma schema.
3. Run prisma generate to generate the Prisma Client. You can then start querying your database.

More information in our documentation:
https://pris.ly/d/getting-started
