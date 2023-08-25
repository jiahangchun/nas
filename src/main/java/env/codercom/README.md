
docker-compose -f src/main/java/env/codercom/compose.yaml up -d

### 密码
这个密码被保存在我们在准备步骤中创建的 “vscode” 目录中的 config.yaml 配置文件中。
要手动创建 .config/code-server/config.yaml 才能正常启动的

bind-addr: 127.0.0.1:8080
auth: password
password: 123456
cert: false

# 文档
[中文教程](https://zhuanlan.zhihu.com/p/380497442)\
[]()