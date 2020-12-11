# 阿里云函数计算 PowerShell 案例

只需几步就可以快速在阿里云函数计算服务上体验 PowerShell ：

- 初始化项目：`s init custom-powershell -p alibaba`
- 进入项目：`cd custom-powershell`
- 安装依赖：`s install docker -f ./fcfile`
- 部署项目：`s deploy`
- 同步依赖: `s nas sync .fun/root`
- 触发项目：`s invoke remote -e "HelloWorld"`

即可实现`PowerShell`案例的初始化、部署整个流程。