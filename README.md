# tesla-spring-cloud-config
tesla configuration 

# regulations 
* /{application}/{profile}[/{label}]
* /{application}-{profile}.yml
* /{label}/{application}-{profile}.yml
* /{application}-{profile}.properties
* /{label}/{application}-{profile}.properties  
```
  application 根据spring.config.name来获得
  profile 激活的环境，比如spring.profiles.active = test
  label git资源的label 默认是master
```
