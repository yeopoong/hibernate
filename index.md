JPA
===

H2 DataBase
-----------

### Download
```
http://www.h2database.com/ 
download 'All Platform' zip file
```

### Execute
```
$ bin/h2.sh
```

### H2 Console

```
$ localhost:8082
```

### Create `MEMBER` table
```
CREATE TABLE MEMBER (
    ID VARCHAR(255) NOT NULL,
    NAME VARCHAR(255),
    AGE INTEGER NOT NULL,
    PRIMARY KEY (ID) 
)
```
