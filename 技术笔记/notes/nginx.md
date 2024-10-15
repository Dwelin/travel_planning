> [notes](../index.md)->nginx

---

#### nginx命令
| 命令 | 用途 |
| :--- | :--- |
| sudo nginx -s reload | 修改配置后重新加载生效 |
| sudo nginx -s reopen | 重新打开日志文件 |
| sudo nginx -s stop | 快速停止nginx |
| sudo nginx -s quit | 完整有序的停止nginx/优雅关闭（先服务完已打开的连接） |