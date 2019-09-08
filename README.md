# php-docker

LAMP + PHPMyadmin base implementation

- You can use MariaDB 10.1 if you checkout to the tag `mariadb-10.1` - contribution made by [luca-vercelli](https://github.com/luca-vercelli)
- You can use MySql 5.7 if you checkout to the tag `mysql5.7`

Run container:

```
$ docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)
Open web browser to look at a simple php example at [http://localhost:8001](http://localhost:8001)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

In the folder www/index.php file contains the phpinfo() function to verify that everything works correctly ;)

Credentials:

BD: myDb
User: user
Password: test
Root Password: test

Enjoy !