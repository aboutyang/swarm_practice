### Docker Swarm 介绍

<p>
Docker Swarm 是 Docker 官方三剑客项目之一，提供 Docker 容器集群服务，是 Docker 官方对容器云生态进行支持的核心方案。使用它，用户可以将多个 Docker 主机封装为单个大型的虚拟 Docker 主机，快速打造一套容器云平台。
</p>
<p>
Docker 1.12.0+ Swarm mode 已经内嵌入 Docker 引擎，成为了 docker 子命令 docker swarm。在安装Docker后，再配置一些属性即可开启Swarm功能
</p>
<p>
本文档是基于CentOS 7.2版本编写的，记录docker swarm的搭建过程；对CentOS 7.2 以下版本或其他操作系统，请自行配置。Docker swarm安装依赖众多第三方库，在安装过程中需要具备公网访问权限。
</p>
