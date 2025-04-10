# party-manager-database
```
party-manager/
├── backend/                # Django后端
│   ├── config/            # 项目配置
│   │   ├── settings/
│   │   │   ├── base.py    # 基础配置
│   │   │   ├── dev.py     # 开发环境
│   │   │   └── prod.py    # 生产环境
│   ├── apps/              # 业务模块
│   │   ├── users/         # 用户管理
│   │   ├── points/        # 积分系统
│   │   └── activities/    # 活动管理
│   └── manage.py
│
├── frontend/              # Vue前端
│   ├── public/
│   ├── src/
│   │   ├── api/           # API接口
│   │   ├── views/         # 页面组件
│   │   └── router/        # 路由配置
│   └── package.json
│
├── docker/                # Docker配置
│   ├── nginx/
│   └── entrypoint.sh      # 容器启动脚本
│
├── requirements/          # Python依赖
│   ├── base.txt           # 基础依赖
│   ├── dev.txt            # 开发依赖
│   └── prod.txt
│
└── README.md              # 项目文档
```
