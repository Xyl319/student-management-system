# 后端设计
## 1. 模块划分
backend/
├── user-auth/ # 用户权限模块（登录、角色管理）
├── student-info/ # 学生信息模块（档案、学籍变动）
├── course-manage/ # 课程管理模块（课程维护、选课）
└── common/ # 公共工具模块（数据库连接、加密）
plaintext

## 2. 技术栈
- 核心框架：Spring Boot 2.7.x
- 持久层框架：MyBatis-Plus
- 数据库：MySQL 8.0
- 缓存：Redis 6.2（可选）

## 3. 数据库设计
- 核心表：
  1. `student`（学生表：id、姓名、学号、班级ID）
  2. `course`（课程表：id、课程名、学期、教师ID）
  3. `user`（用户表：id、账号、密码、角色）
