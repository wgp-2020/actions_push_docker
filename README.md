# Push Docker Image

使用GitHub Action制作镜像并推送到DockerHub

**添加账号**（[设置秘密变量](settings/secrets/actions)）

- `USERNAME`：用户名
- `PASSWORD`：密码

设置仓库与镜像名（[运行Action](actions/workflows/main.yml)）

- 目标仓库，示例：`wgp-2020/push_docker_image`
- 镜像名称，示例：`username/demo:latest`
