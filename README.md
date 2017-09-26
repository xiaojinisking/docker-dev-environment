# docker-dev-environment
dokcer创建的一些开发环境

### php-dev-enviroment 
***php的开发环境***
   
    git clone xxxx
    chmod -R 777 php-dev-environment
    cd php-dev-environment
    sudo docker-compose up -d
    
    
-    数据库连接：
    $dbh = new PDO('mysql:host=mysql;dbname=xxx', 'root', 123456);