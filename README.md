# Clinic Management System

## Deskripsi
Project ini merupakan sistem manajemen klinik berbasis Laravel yang dijalankan menggunakan Ubuntu Server pada VirtualBox dengan Apache2 dan MySQL.

---

# Teknologi yang Digunakan

- Ubuntu Server
- Apache2
- PHP
- Laravel
- MySQL
- VirtualBox

---

# Cara Clone dan Menjalankan Project

## Clone Repository

```bash
git clone https://github.com/n4ilong-f0rg0t/clinic-management-system.git
```

---

## Copy File Environment

```bash
cp .env.example .env
```

---

## Install Dependency Laravel

```bash
composer install
```

---

## Generate Application Key

```bash
php artisan key:generate
```

---

## Membuat Symbolic Link Storage

```bash
php artisan storage:link
```

---

## Migrasi Database

```bash
php artisan migrate
```

---

## Seeder Database

```bash
php artisan db:seed
```

---

# Akses Website

Buka browser:

```text
http://IP-SERVER
