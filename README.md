# Build Status

## Wercker

[![wercker status](https://app.wercker.com/status/f90009239132fc2454903eab780a81ac/s/master "wercker status")](https://app.wercker.com/project/byKey/f90009239132fc2454903eab780a81ac)

## CircleCI

[![CircleCI](https://circleci.com/gh/microservices-aspnetcore-zh/hello-world.svg?style=svg)](https://circleci.com/gh/microservices-aspnetcore-zh/hello-world)

# Hello World

这是书中第一个示例。它使用 `wercker.yml` 文件控制 Wercker 自动构建的方式。每次签入代码之后，Wercker 就会构建项目，并部署到 docker hub。

可以在[此处](https://hub.docker.com/r/dotnetcoreserviceszh/hello-world/tags)查看此工程的 docker 镜像。

## 注释
由于测试时wercker已经注册不了(人机验证弹框不出)，所以建议若有人重新按照此书进行学习，直接使用circleCI即可，circleCI在本次提交时(2022-01-25)，配置文件默认路径为.circleci/config.yml，本处的circle.yml配置仍然会运行成功无需修改。而且由于jenkins和github action也可以支持了，建议尝试。
由于更新到.NET6，语法部分已经做了很大修改 为了与书本保持一致，只修改了docker及项目依赖包