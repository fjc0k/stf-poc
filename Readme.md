# STF

[STF](https://github.com/openstf/stf) 的 Docker Compose 编排。

派生自 [nikosch86/stf-poc](https://github.com/nikosch86/stf-poc)，其仅可用于 Linux 服务器。

本派生版本仅适用于 Mac 电脑和 Windows 电脑，请根据你的使用场景选用。

## 如何安装

- 首先，在你的设备上安装 [Docker](https://docs.docker.com/get-docker/) 和 [Docker Compose](https://docs.docker.com/compose/install/)。

- 然后，在你的设备上安装 [adb](https://developer.android.com/studio/releases/platform-tools) 并启动：

  ```bash
  adb start-server -a
  ```

- 最后，克隆本仓库，并启动 Docker Compose 编排：

  ```bash
  # 克隆仓库
  git clone https://github.com/fjc0k/stf-poc.git

  # 切换到仓库目录
  cd stf-poc

  # 编排启动
  docker-compose up -d --build
  ```

## 如何访问

浏览器打开 `http://127.0.0.1:9090` 输入管理员名称、邮箱即可访问：

- 名称：`administrator`
- 邮箱：`administrator@fakedomain.com`

## 许可

Jay Fong (c) MIT