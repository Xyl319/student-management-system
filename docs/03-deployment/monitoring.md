# 监控和日志查看
## 1. 日志查看
- 后端日志：`tail -f /opt/app/app.log`
- Nginx日志：`tail -f /var/log/nginx/access.log`

## 2. 服务监控
- 查看进程：`ps -ef | grep java`
- 重启服务：`./stop.sh && ./start.sh`
