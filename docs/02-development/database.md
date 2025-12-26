# 数据库指南
## 1. ER图
student（学生）───┐
│student_course（选课）│
│course（课程）────┘

## 2. 迁移脚本
初始化脚本：`sql/init.sql`（创建核心表+测试数据）

## 3. 备份方案
- 自动备份：Linux定时任务+`mysqldump`
- 手动备份：`mysqldump -u root -p 库名 > 备份文件.sql`
