# prisma-postgresql-pgadmin-example
### Source
https://www.prisma.io/docs/tutorials/bootstrapping-boilerplates/react-(fullstack)-tijghei9go/

![image](https://user-images.githubusercontent.com/97060/46254389-f0561500-c4b8-11e8-9ae5-84f7727005f6.png)

### To develop
1. Up `prisma`, `postgres`, `pgadmin`
![image](https://user-images.githubusercontent.com/97060/46247676-2a7fd200-c439-11e8-9998-5a192bf1856d.png)
    ```
    cd dev
    . up
    ```
1. Prisma server
![image](https://user-images.githubusercontent.com/97060/46247693-5e5af780-c439-11e8-8b69-a866d1a3504e.png)
    ```
    cd web/server
    yarn dev
    ```
1. Apollo web client
![image](https://user-images.githubusercontent.com/97060/46247787-b0e8e380-c43a-11e8-8550-c83d7a2f2b8e.png)
    ```
    cd web
    yarn install
    yarn start
    ```
    - email : `developer@example.com`
    - password : `nooneknows`
1. PostgreSQL admin
![image](https://user-images.githubusercontent.com/97060/46247600-e8a25c00-c437-11e8-9fc0-43bf77b13d18.png)
    - open `http://localhost:5050`
    - Connection : `postgres`
    - SSL : `Disable`
    
