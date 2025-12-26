编写文档目的：规范团队开发流程，明确分支命名、提交规范、PR 要求，确保协作高效有序。
内容模板：
# 贡献指南
感谢您对学生学籍管理系统的关注与贡献！本指南将帮助您快速参与项目开发。

## 1. 开发工作流
本项目采用 **GitHub Flow** 工作流，核心流程如下：
1. 从`main`分支创建功能/修复分支
2. 在分支上完成开发与测试
3. 提交PR到`main`分支
4. 代码评审通过后合并到`main`分支
5. 删除已合并的临时分支

## 2. 分支命名规范
分支命名格式：`类型/简短描述`，类型包括：
- `feat/xxx`：新增功能（如`feat/add-score-export`）
- `fix/xxx`：修复Bug（如`fix/login-validation`）
- `docs/xxx`：文档更新（如`docs/update-api-doc`）
- `refactor/xxx`：代码重构（如`refactor/optimize-db-query`）
- `test/xxx`：测试相关（如`test/add-student-service-test`）

## 3. 提交信息规范
提交信息格式：`[类型] 描述`，示例：
- `[feat] 新增学生成绩导出功能`
- `[fix] 修复学生学籍状态更新失败问题`
- `[docs] 补充数据库设计文档`

## 4. Pull Request（PR）模板
提交PR时需包含以下信息：
1. **关联Issue**：链接对应的Issue（如`Fixes #12`）
2. **功能描述**：简要说明本次PR实现的功能或修复的问题
3. **测试情况**：说明已完成的测试（如单元测试、功能测试）
4. **截图/录屏**（可选）：UI相关变更需附上截图，功能变更可附操作录屏
5. **注意事项**：如依赖调整、需同步更新的配置等

## 5. 代码规范
- 后端代码：遵循阿里巴巴Java开发手册（泰山版）
- 数据库操作：禁止直接拼接SQL，使用参数化查询防止注入
- 注释要求：类、公共方法需添加Javadoc注释，复杂逻辑需添加行内注释

## 6. 问题反馈
若开发过程中遇到问题，可通过以下方式沟通：
- 提交Issue：详细描述问题场景、复现步骤
- 团队会议：每周五16:00召开开发同步会，可提前提交议题
         *  开发工作流：明确使用的Git工作流（如：Git Flow, GitHub Flow, Trunk Based Development）。
        *  分支命名规范：例如 `feat/add-user-login`, `fix/header-overflow`, `docs/update-readme`。
        *   Pull Request 模板：描述PR需要包含哪些信息（链接到Issue、截图、测试情况等）。
