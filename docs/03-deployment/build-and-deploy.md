# 构建与部署
## 1. 项目构建
1. 清理：`mvn clean`
2. 打包：`mvn package -Dmaven.test.skip=true`
3. 产物：`target/student-management-system-1.0.0.jar`

## 2. 部署到服务器
1. 上传jar包：`scp 包路径 root@服务器IP:/opt/app`
2. 启动：`nohup java -jar 包名 > app.log 2>&1 &`
