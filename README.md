# 什么是docker





![What is Docker ? How to use it ? - Knoldus Blogs](data:image/png;base64,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)

Docker 是一个开源的容器化平台，用于构建、打包和运行应用程序。它允许开发人员将应用程序及其依赖项打包到一个称为容器的独立单元中，以便在不同的环境中进行部署和运行。

与传统的虚拟化技术相比，Docker 使用容器化的方式更加轻量级和灵活。每个容器都包含应用程序、运行时环境和依赖项，它们之间相互隔离，但共享主机操作系统的内核。这使得容器可以在不同的操作系统和硬件平台上运行，而无需修改应用程序代码。

Docker 提供了一组工具和命令行接口，使开发人员可以方便地构建、管理和部署容器。以下是一些 Docker 的核心概念和组件：

1. 镜像（Image）：镜像是一个只读的模板，包含了运行应用程序所需的所有文件和配置。开发人员可以使用 Dockerfile 来定义镜像的构建过程，然后使用 Docker 构建工具将其生成。
2. 容器（Container）：容器是从镜像创建的运行实例。每个容器都是相互隔离的，具有自己的文件系统、进程空间和网络接口。容器可以启动、停止、删除和管理。
3. 仓库（Repository）：仓库是用于存储和共享镜像的地方。Docker Hub 是一个公共的仓库，你可以在其中找到许多常见的镜像。此外，你还可以创建私有仓库来存储自己的镜像。