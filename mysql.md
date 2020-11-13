[TOC]
# mysql配置情况  
## mysql的密码查看及修改
> 查看初始密码：  
    ```mysql
    sudo vim /etc/mysql/debian.cnf
    ```
> 修改密码  
    ```mysql
    ALTER user 'root'@'localhost' identified with mysql_native_password by 'swpturgan';
    ```
