###### 发布第三方jar到本地镜像库
```
/mvn deploy:deploy-file -DgroupId=com.oracle -DartifactId=ojdbc14 -Dversion=10.2.0.5.0 -Dpackaging=jar -Durl=http://ip:port/repository/3rd/ -DrepositoryId=releases  -Dfile=ojdbc.jar 

``` 

###### npm命令
1. npm cache clean
2. npm set registry=url
3. npm publish --registry url
4. npm adduser
5. npm install xxx -f
