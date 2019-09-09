# spring-cloud-config
远程配置中心

文件的命名规则：
/{applicationName}-{profile}.yml  :  /cloud-config-client-dev.yml

spring:
  application:
    name: cloud-config-client
    
 
 
/{applicationName}-{profiles}.yml
/{label}/{name}-{profiles}.yml

applicationName : 文件名，一般以服务名来命名
profiles : 一般作为环境标识 dev pro test 
lable : 分支（branch），指定访问某分支下的配置文件 默认为master
    
