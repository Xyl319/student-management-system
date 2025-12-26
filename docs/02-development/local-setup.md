# 本地开发环境搭建指南
## 1. 依赖安装
### 1.1 安装JDK 11
- 下载地址：[OpenJDK官网](https://adoptium.net/)
- 配置环境变量：设置`JAVA_HOME`，添加到`Path`

### 1.2 安装MySQL 8.0
- 下载地址：[MySQL官网](https://dev.mysql.com/)
- 初始化：创建数据库`student_management_db`

## 2. 项目运行
1. 克隆代码：`git clone 仓库地址`
2. 配置数据库：修改`application.properties`中的连接信息
3. 启动项目：IDEA中运行主类

## 3. 常见问题排查
- 数据库连接失败：检查MySQL是否启动、密码是否正确
- 端口占用：修改`server.port`为未占用端口
