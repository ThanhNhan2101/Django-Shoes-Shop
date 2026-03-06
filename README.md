# Shoe Store Website 👟

## Introduction

Shoe Store Website là một dự án web thương mại điện tử cho phép người
dùng tìm kiếm, xem và mua giày trực tuyến. Hệ thống cung cấp các chức
năng cơ bản của một website bán hàng như đăng ký, đăng nhập, xem sản
phẩm, quản lý giỏ hàng và thanh toán.

Dự án được xây dựng nhằm mục đích luyện tập và thể hiện kỹ năng phát
triển **Back‑end với Python/Django**.

------------------------------------------------------------------------

## Features

### Authentication

-   Đăng ký tài khoản
-   Đăng nhập / Đăng xuất
-   Chỉnh sửa thông tin cá nhân

### Product Management

-   Xem danh sách sản phẩm
-   Xem chi tiết sản phẩm
-   Lọc sản phẩm theo nhiều tiêu chí

### Shopping Cart

-   Thêm sản phẩm vào giỏ hàng
-   Xem giỏ hàng
-   Cập nhật số lượng sản phẩm
-   Xóa sản phẩm khỏi giỏ hàng

### Checkout

-   Xem tổng tiền đơn hàng
-   Nhập thông tin cá nhân
-   Áp dụng mã giảm giá (voucher)
-   Xác nhận thanh toán

### Order Management

-   Xem lịch sử mua hàng
-   Xem chi tiết đơn hàng

------------------------------------------------------------------------

## Technologies Used

### Backend

-   Python
-   Django
-   Django REST Framework

### Frontend

-   HTML
-   CSS
-   JavaScript

### Database

-   SQLite / PostgreSQL

### Tools

-   Git
-   Postman

------------------------------------------------------------------------

## Project Structure

    shoe-store
    │
    ├── users
    │   └── quản lý đăng nhập, đăng ký, thông tin người dùng
    │
    ├── products
    │   └── quản lý sản phẩm và filter
    │
    ├── cart
    │   └── quản lý giỏ hàng
    │
    ├── orders
    │   └── quản lý đơn hàng và lịch sử mua
    │
    └── vouchers
        └── hệ thống mã giảm giá

------------------------------------------------------------------------

## Main User Flow

1.  Người dùng đăng ký hoặc đăng nhập vào hệ thống
2.  Người dùng xem danh sách sản phẩm
3.  Người dùng lọc sản phẩm theo nhu cầu
4.  Người dùng thêm sản phẩm vào giỏ hàng
5.  Người dùng kiểm tra giỏ hàng
6.  Người dùng tiến hành thanh toán
7.  Người dùng xem lịch sử đơn hàng

------------------------------------------------------------------------

## Installation

Clone project

``` bash
git clone https://github.com/yourusername/shoe-store.git
```

Tạo virtual environment

``` bash
python -m venv venv
```

Kích hoạt môi trường

``` bash
venv\Scripts\activate
```

Cài đặt dependencies

``` bash
pip install -r requirements.txt
```

Chạy server

``` bash
python manage.py runserver
```

------------------------------------------------------------------------

## Author

**Thanh**\
Backend Developer (Python/Django)
