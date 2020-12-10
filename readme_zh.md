# 阿里云函数计算：custom-powershell

通过该应用，您可以简单快速地在阿里云函数计算创建一个 custom-powershell 服务。

- 下载命令行工具：`npm install -g @serverless-devs/s`

- 配置账号信息，以阿里云为例。
    1. 获取账号Id： https://account.console.aliyun.com/#/secure
        ![](https://images.serverlessfans.com/s-tool/zh/start-1.jpg)
    2. 获取密钥信息：https://ram.console.aliyun.com/manage/ak
        ![](https://images.serverlessfans.com/s-tool/zh/start-2.jpg)
    3. 通过`s config add`进行项目配置
        ![](https://images.serverlessfans.com/s-tool/zh/start-3.jpg)

- 初始化一个模版项目：`s init custom-powershell -p alibaba`
- 进入项目：`cd custom-powershell`

- 执行 `s install docker -f ./fcfile` 安装依赖。

- 执行 `s deploy` 进行部署。

- 执行 `s nas sync .fun/root` 将依赖同步至 NAS

- 至此，我们完成了简单的函数部署功能。

- 最后，执行 `s invoke remote -e hello-powershell` 即可进行远程调用。

