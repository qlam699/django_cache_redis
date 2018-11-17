# Django cache redis 

#### ref: code.tutsplus.com/tutorials/how-to-cache-using-redis-in-django-applications--cms-30178

#Install
```
pip install django==1.9
pip install django-redis
pip install djangorestframework
pip install redis==2.10.6
```

# Test
## install:
npm install -g loadtest

## Run 
$ loadtest -n 100 -k  http://localhost:8000/store/
 
#### result
INFO Requests per second: 55


$ loadtest -n 100 -k  http://localhost:8000/store/cache/
 
#### results
INFO Requests per second: 233