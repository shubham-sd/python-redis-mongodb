# python-redis-mongodb
getting data from mongodb and set to redis with python

## Getting Started
Main goal of this project helping the beginners on python like me who want to use mongodb and redis at the same python project.

### Prerequisites

Install redis server, mongodb and python to windows.

Install redis and mongodb packages for python using pip.


```
 C:\Python\Scripts> pip install pymongo
 C:\Python\Scripts> pip install redis
```


Create a database to mongodb(DummyDb) and collection(Users) using robomongo or one of the mongodb guis. i prefer the robomongo.

Insert data to "Users" collection

```
{
    "username" : "mert",
    "email" : "dummy@mongoredispython.com",
    "age" : 25
}
```
