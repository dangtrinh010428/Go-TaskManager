GO_TASKMANAGER/
├── cmd/
│   ├── cli/
│   │   └── main.go
│   ├── cronjob/
│   │   └── main.go
│   └── server/
│       └── main.go
│
├── configs/
│   ├── local.yaml
│   ├── development.yaml
│   └── production.yaml
│
├── docs/
│   ├── swagger.json
│   └── swagger.yaml
│
├── global/
│   └── global.go
│
├── internal/
│   ├── controller/
│   │   ├── auth_controller.go
│   │   ├── user_controller.go
│   │   ├── project_controller.go
│   │   ├── task_controller.go
│   │   ├── comment_controller.go
│   │   └── notification_controller.go
│   │
│   ├── init/
│   │   ├── init_config.go
│   │   ├── init_database.go
│   │   ├── init_logger.go
│   │   ├── init_redis.go
│   │   └── init_router.go
│   │
│   ├── middlewares/
│   │   ├── auth_middleware.go
│   │   ├── role_middleware.go
│   │   ├── cors_middleware.go
│   │   ├── logger_middleware.go
│   │   └── recovery_middleware.go
│   │
│   ├── models/
│   │   ├── user.go
│   │   ├── project.go
│   │   ├── project_member.go
│   │   ├── task.go
│   │   ├── task_comment.go
│   │   ├── task_activity.go
│   │   ├── notification.go
│   │   └── refresh_token.go
│   │
│   ├── repo/
│   │   ├── user_repo.go
│   │   ├── project_repo.go
│   │   ├── task_repo.go
│   │   ├── comment_repo.go
│   │   └── notification_repo.go
│   │
│   ├── routers/
│   │   ├── router.go
│   │   ├── auth_router.go
│   │   ├── user_router.go
│   │   ├── project_router.go
│   │   ├── task_router.go
│   │   ├── comment_router.go
│   │   └── notification_router.go
│   │
│   └── services/
│       ├── auth_service.go
│       ├── user_service.go
│       ├── project_service.go
│       ├── task_service.go
│       ├── comment_service.go
│       └── notification_service.go
│
├── migrations/
│   ├── 000001_create_users.up.sql
│   ├── 000001_create_users.down.sql
│   ├── 000002_create_projects.up.sql
│   ├── 000002_create_projects.down.sql
│   ├── 000003_create_tasks.up.sql
│   └── 000003_create_tasks.down.sql
│
├── pkg/
│   ├── loggers/
│   │   └── logger.go
│   ├── response/
│   │   └── response.go
│   ├── settings/
│   │   └── config.go
│   └── utils/
│       ├── jwt.go
│       ├── password.go
│       ├── pagination.go
│       └── validator.go
│
├── scripts/
├── tests/
├── third_party/
│   ├── mail/
│   └── storage/
├── web/
├── go.mod
└── go.sum