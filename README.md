# iTask Manager

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Release](https://img.shields.io/badge/release-v0.1.0-orange)
![Go](https://img.shields.io/badge/Go-1.26-00ADD8?logo=go&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue)

## Tổng quan

**iTask Manager** là hệ thống quản lý công việc được xây dựng bằng **Golang**, hỗ trợ tổ chức dự án, phân công nhiệm vụ, theo dõi tiến độ và quản lý thành viên trong nhóm.

Dự án được phát triển theo kiến trúc phân tầng:

```text
Router → Middleware → Controller → Service → Repository → Database
```

Mục tiêu của dự án là xây dựng một RESTful API có cấu trúc rõ ràng, dễ bảo trì và có thể mở rộng cho các hệ thống quản lý công việc thực tế.

## Chức năng chính

- Đăng ký, đăng nhập và xác thực bằng JWT.
- Quản lý người dùng và phân quyền.
- Quản lý dự án và thành viên dự án.
- Tạo, cập nhật, phân công và theo dõi công việc.
- Quản lý trạng thái và mức độ ưu tiên của công việc.
- Bình luận trong công việc.
- Theo dõi lịch sử hoạt động.
- Quản lý thông báo.
- Tìm kiếm, lọc và phân trang danh sách công việc.
- Tài liệu API bằng Swagger.

## Công nghệ sử dụng

- **Golang**
- **Gin**
- **PostgreSQL**
- **GORM**
- **Redis**
- **JWT**
- **Swagger**
- **Docker**

## Cấu trúc dự án

```text
GO_TASKMANAGER/
├── cmd/
│   ├── cli/
│   ├── cronjob/
│   └── server/
├── configs/
├── docs/
├── global/
├── internal/
│   ├── controller/
│   ├── init/
│   ├── middlewares/
│   ├── models/
│   ├── repo/
│   ├── routers/
│   └── services/
├── migrations/
├── pkg/
├── scripts/
├── tests/
├── third_party/
├── web/
└── go.mod
```

## Trạng thái dự án

Phiên bản hiện tại: **v0.1.0**

## Giấy phép

Dự án được phát hành theo giấy phép [Apache License 2.0](LICENSE).
