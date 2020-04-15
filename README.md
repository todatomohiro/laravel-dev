# laravel-dev

Docker上でLaravel環境を構築

## 簡単な説明

Blogトモテクで掲載されている「Dockerを使って開発環境を構築する」を  
簡単に試せるようにGitHubにスクリプトを用意しています。  

Blog URL : https://develop.blue/2020/04/laravel-docker-setup/

## 必要要件

- Dockerが動作可能な環境

## 開発環境:Docker (2020/04/04)

- Nginx : 1.17.9
- PHP : 7.2.29
- MySQL : 5.7
- Laravel : 7.5.2

## セットアップ

cd laravel-dev/  
docker-compose up -d  
docker-compose exec php bash
laravel new

## 導入されるファイル

 /src  
 　Laravelフレームワーク   
   
 /docker/db  
 　MySQLの保存データ  

## 作者

Name: Toda Tomohiro  
WebSite: https://develop.blue/

## ライセンス

MIT License