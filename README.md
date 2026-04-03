# 🚀 AWS WordPress Deployment using EC2 + RDS (MariaDB)

This project demonstrates deploying a production-style WordPress application using AWS services including EC2, RDS (MariaDB), and secure networking.

---

## 📌 Architecture Overview

- EC2 instance (Apache + PHP)
- RDS MariaDB instance (database layer)
- Security Groups for controlled access
- Public access via EC2 HTTP (port 80)

---

## ⚙️ Technologies Used

- AWS EC2
- AWS RDS (MariaDB)
- Apache (httpd)
- PHP 8.x
- WordPress
- Linux (Amazon Linux)

---

## 🛠️ Setup Steps

### 1. EC2 Configuration

Installed required packages:

```bash
sudo yum update -y
sudo yum install -y wget httpd php php-mysqlnd php-fpm php-mysqli php-json php-devel mariadb105-server
