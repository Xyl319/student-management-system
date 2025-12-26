# 变更日志
本项目所有显著变更都将记录在此文件中。
格式遵循 [Keep a Changelog](https://keepachangelog.com/)，版本号遵循 [Semantic Versioning](https://semver.org/)。

## [未发布]
### Added
- 新增README.md、CONTRIBUTING.md、CHANGELOG.md核心文档
- 新增学生档案管理基础功能（新增、查询、修改、删除学生信息）
- 新增MySQL数据库连接配置

### Changed
- 优化项目目录结构，区分源代码和配置文件

### Fixed
- 修复数据库连接时用户名密码明文存储问题（改为加密存储）

## [1.0.0] - 2025-12-23
- 项目正式初始化，完成核心功能开发：
  1. 多角色权限管控（管理员、教师、学生）
  2. 全流程学籍管理（注册、变动、毕业审核）
  3. 基础课程管理（按学期维护课程）
