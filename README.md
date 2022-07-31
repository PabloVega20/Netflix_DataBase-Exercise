# WTF

- Crear las tablas con el Script
- Ir a aplicaciones properties y cambiar la base de datos


-> Para acceder a la base datos desde terminal habrá que hacer lo siguiente:
    - mysql -hserver -ugftxx -pgftxx (xx remplazar por vuestro número)
    - Ir a gftxx
    - Copiar y pegar todo el esquema

truncate table actor;
truncate table title;
truncate table director;
truncate table category;
truncate table title_actor;
truncate table title_director;
truncate table title_category;

<dependency>            
        <groupId>org.springframework.boot</groupId>            
        <artifactId>spring-boot-starter-data-rest</artifactId>        
</dependency>

