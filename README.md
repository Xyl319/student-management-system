# 学生学籍管理系统

[![GitHub license](https://img.shields.io/github/license/Xyl319/student-management-system)](https://github.com/Xyl319/student-management-system)

> 基于Spring Boot+MySQL开发的学生学籍管理系统，支持学生档案、学籍、班级、课程信息的数字化管理，适配中小型院校教务管理需求。

## 核心特性
- 特性1：多角色权限管控：区分管理员、教师、学生角色，实现权限隔离
- 特性2：全流程学籍管理：覆盖学生注册、学籍变动、毕业审核、证书生成全流程
- 特性3：灵活课程管理：支持按学期/班级维护课程，多条件查询课程信息
- 特性4：数据安全保障：支持自动/手动数据备份，敏感信息加密存储

## 快速开始
### 先决条件
- Python 3.8+
- Git
- JDK 11+
- MySQL 8.0+
- Maven 3.6+

### 安装与运行
1. 克隆仓库：`git clone git@github.com:Xyl319/student-management-system.git`
2. 进入项目目录：`cd student-management-system`
3. 配置数据库：修改 `src/main/resources/application.properties` 文件中的MySQL连接信息（用户名、密码、数据库名）
4. 构建项目：`mvn clean install`（若用Maven）
5. 运行项目：`java -jar target/student-management-system-1.0.0.jar`（jar包名按实际情况修改）

## 项目结构
├── src/ # 源代码（Java 类、配置文件）
│ ├── main/
│ │ ├── java/ # Java 业务代码
│ │ └── resources/ # 配置文件（数据库配置、静态资源）
│ └── test/ # 测试代码
├── docs/ # 详细文档（后续可添加架构图、数据库 ER 图）
├── pom.xml # Maven 依赖配置（若用 Maven）
├── README.md # 项目自述（本文档）
├── CONTRIBUTING.md # 贡献指南
└── CHANGELOG.md # 变更日志
└── LICENSE # 许可证文件

## 如何贡献
我们欢迎所有形式的贡献！请先阅读 [贡献指南](CONTRIBUTING.md)。

## 许可证
本项目基于 [MIT许可证](LICENSE) 开源（若选其他许可证，替换为对应名称）。

## 获取帮助
- [提交Issue](https://github.com/Xyl319/student-management-system/issues)：报告Bug或提出新特性建议
- 联系作者：2364709407@qq.com
