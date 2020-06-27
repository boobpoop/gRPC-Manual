gRPC相关代码
===========

本仓库包含gPRC的一些项目，这些项目由简到易，解释了框架底层原理。通过适当注释，可以帮助开发者学习如何使用该框架。知其然，知其所以然。

<table>
  <tr>
    <td><b>作者</b></td>
    <td><b>yuliang</b></td>
  </tr>
  <tr>
    <td><b>邮箱</b></td>
    <td><b>yulianggo@yeah.net</b></td>
  </tr>
</table>

# gRPC_Java安装--避坑指南
1. [gRPC_Java官网安装流程](https://www.grpc.io/docs/languages/java/quickstart/)<br>
2. 注意要在mac中的环境变量配置中引入JAVA_HOME地址。本人在.bash_profile配置文件中的JAVA_HOME配置为：<br>
>  export JAVA_HOME="/Library/Java/JavaVirtualMachines/jdk1.8.0_221.jdk/Contents/Home"<br>

3. 修改build.gradle和settings.gradle文件中maven仓库中的url，原始url无法下载protocol插件。新的url:<br>
> https://plugins.gradle.org/m2/<br>


# 钩子回调
异步

# 流式传输
todo
