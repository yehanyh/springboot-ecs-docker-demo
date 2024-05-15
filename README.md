# 代码仓库结构

文档目录说明：
```
├── README.md                   - README
├── docs                        - 服务文档相关文件
│   └── index.md
├── resources                   - 服务资源文件
│   ├── icons
│   │   └── logo.png            - 服务logo
│   └── artifact_resources      - 部署物相关资源文件
│       └── file                - 文件部署物目录
│           └── package.tgz    
│       └── acr_image           - acr镜像部署物目录
│           └── Dockerfile      - 用于构建镜像的Dockerfile
├── ros_templates               - 服务ROS模板，可以有多个
│   └── template.yaml           - 示例ROS模板
├── config.yaml                 - 服务配置文件
```