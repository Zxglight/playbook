### 安装并启动logstash

目前支持的平台:

RHEL/Centos(6.x/7.x)

需要参数信息:
```json
{
  "content":"logstash启动配置文件内容",
  "ftpip":"localhost"
}
```

执行命令:
```bash
 ansible-playbook site.yml -i hosts --extra-var="@var.json"
```