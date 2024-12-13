# 使用工具與環境安裝

## 使用工具
前端：html  
後端：laravel, php  
資料庫：Maria DB  

## 安裝環境

### 後端

#### 安裝php主程式  
https://windows.php.net/download/  

下載zip檔，解壓縮，放到C槽
![](readme/php%E4%B8%8B%E8%BC%89.PNG)
圖(php下載)  
![](readme/php%E5%9C%A8C%E6%A7%BD.PNG)
圖(php在C槽)  

設定環境變數  
![](readme/%E8%A8%AD%E5%AE%9A%E7%92%B0%E5%A2%83%E8%AE%8A%E6%95%B8.PNG)
圖(設定環境變數)  

在cmd輸入，確認php是否安裝成功
```
php -v
```

複製php.ini-development然後命名為php.ini  
![](readme/%E8%A4%87%E8%A3%BDphpini.PNG)
圖(複製phpini)  
![](readme/%E5%91%BD%E5%90%8D%E7%82%BAphpini.PNG)
圖(命名為phpini)  

在cmd輸入，確認Loaded Configuration File有找到檔案
![](readme/%E7%A2%BA%E8%AA%8D%E6%9C%89phpini.PNG)
圖(確認有phpini)  

#### 安裝composer  
https://getcomposer.org  

按download，找Composer-Setup.exe來下載
![](readme/%E4%B8%8B%E8%BC%89composer.PNG
圖(下載composer)

安裝composer  
![](readme/%E5%AE%89%E8%A3%9Dcomposer1.PNG)
圖(安裝composer1)  
![](readme/%E5%AE%89%E8%A3%9Dcomposer2.PNG)
圖(安裝composer2)  
![](readme/%E5%AE%89%E8%A3%9Dcomposer3.PNG)
圖(安裝composer3)  
![](readme/%E5%AE%89%E8%A3%9Dcomposer4.PNG)
圖(安裝composer4)  
![](readme/%E5%AE%89%E8%A3%9Dcomposer5.PNG)
圖(安裝composer5)  
![](readme/%E5%AE%89%E8%A3%9Dcomposer6.PNG)
圖(安裝composer6)  


在cmd輸入，確認composer是否安裝成功
```
composer -v
```

#### 安裝laravel
在cmd輸入，以安裝laravel
```
composer global require Laravel/installer
```
確認laravel是否安裝成功
```
lrarvel -v
```
### 資料庫
### 安裝Ｍaria DB  
https://mariadb.org/download/?t=mariadb&p=mariadb&r=11.4.0  
下載Maria DB
![](readme/%E4%B8%8B%E8%BC%89DB.PNG)
匯入.sql

以上安裝完畢

## 執行

在專案下開terminal，輸入
```
php artisan server
```
用網頁打開它給你的IP，完畢