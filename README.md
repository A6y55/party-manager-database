# party-manager-database
```
party-manager/
├── backend/               # Django后端
│   ├── party_manager/     # 项目主目录
│   │   ├── __init__.py
│   │   ├── settings.py    # 合并后的统一配置
│   │   ├── urls.py        # 主路由
│   │   └── wsgi.py
│   ├── apps/              # 应用模块
│   │   ├── users/         # 用户管理
│   │   │   ├── models.py
│   │   │   └── views.py
│   ├── manage.py
│   └── requirements.txt   # 统一依赖文件
│
├── frontend/              # Vue前端
│   ├── src/
│   │   ├── api/           # 接口层
│   │   │   └── auth.js    # 示例接口
│   │   ├── views/         # 页面组件
│   │   │   └── UserList.vue
│   │   └── main.js        # 入口文件
│   ├── package.json
│   └── vue.config.js      # 开发代理配置
│
├── .gitignore
└── README.md              # 简明启动指南
```
