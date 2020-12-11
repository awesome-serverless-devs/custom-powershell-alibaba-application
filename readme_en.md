# Alibaba cloud function computing PowerShell case

You can quickly experience PowerShell on Alibaba Cloud function computing services in these steps:

- Initialization project: ` s init custom-powershell -p alibaba`
- Enter project: `cd custom-powershell`
- Install dependencies：`s install docker -f ./fcfile`
- Deployment project: `s deploy`
- Sync dependencies: `s nas sync .fun/root`
- Invoke project：`s invoke remote -e "HelloWorld"`

The whole process of initialization and deployment of `PowerShell` cases can be realized.