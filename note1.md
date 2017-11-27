###### 发布第三方jar到本地镜像库
```
/mvn deploy:deploy-file -DgroupId=com.oracle -DartifactId=ojdbc14 -Dversion=10.2.0.5.0 -Dpackaging=jar -Durl=http://ip:port/repository/3rd/ -DrepositoryId=releases  -Dfile=ojdbc.jar 

``` 
