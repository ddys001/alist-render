# alist-render

### Deploy Alist to Render
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

### database
You may need to use another remote MySQL database as instance restarts will lose data.
Recommended Free MySQL Databases:
- https://db4free.net/
- https://remotemysql.com/
- https://www.freesqldatabase.com/

### password
The initial password is randomly generated, and you can get it by checking the `logs`.

### 变量设置

| 变量参数	  | 示例参数	   | 数据库详情页对应   
|-----------|--------------|:------:| 
| DB_HOST	| queenie.db.elephantsql.com	|Server
| DB_NAME	| bkqgx	User & Default | database
| DB_PASS	| 5CqBjEVZWdaaad2333aadadadadN3Clo	| Password	
| DB_SSL_MODE	| disable		
| DB_TYPE	| postgres		
| DB_USER	| bkqgx	| User & Default database
| PORT	| 8080	
