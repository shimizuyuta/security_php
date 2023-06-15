## 概要
- ハンズオン形式の書籍なので仮想環境を作り実践的に学ぶ。
- セキュリティについて知らないことが多いので「安全なWebアプリケーションの作り方」をやる
![image](https://github.com/shimizuyuta/security_php/assets/58338829/8337dd96-9811-4783-87a1-69602ab9644a)

## 目的
- Qiitaアウトプットネタを作る
- 脆弱性の原理と対策を学ぶ

## 前提
書籍ではVMware Playerを使用しているが、今回はDockerを使用。

## 環境
- Mac M2
- Docker
 - php:7.4-apache
 - postgres:13
 - phpMyAdmin   


## 構成
```
/myproject
│
├── .env
│
├── docker-compose.yml
│
├── src
│   ├── index.php
│   └── ... (その他のPHPファイル)
│
├── db-init
│   ├── 01_create_tables.sql
│   └── ... (その他のSQLスクリプト)
│
└── ... (その他のファイルやディレクトリ)
```
# 
