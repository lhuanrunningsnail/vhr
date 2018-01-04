微人事是一个前后端分离的人力资源管理系统，项目采用SpringBoot+Vue开发。  


演示地址：  

项目地址：[https://github.com/lenve/vhr](https://github.com/lenve/vhr)  


## tips 

>由于整个项目功能比较多，也比较复杂，因此分多期开发，目前第一期权限管理模块已经开发完成，其他模块还在开发当中。考虑到权限管理模块相对独立，和其他模块的功能并不冲突，同时前后端分离之后的权限管理又是许多小伙伴的痛点，因此将本项目提前开源供小伙伴们研究。**但是小伙伴们需要注意的是，目前只有权限管理模块完工了，因此这个项目中你无法看到所有的功能，除了权限管理相关的模块。权限管理相关的模块主要有两个，分别是 ***系统管理->基础信息设置->权限组***可以管理角色和资源的关系，***系统管理->操作员管理***可以管理用户和角色的关系。**  


## 技术栈

### 后端技术栈

1.SpringBoot  
2.SpringSecurity  
3.MyBatis  
4.MySQL  

### 前端技术栈

1.Vue  
2.ElementUI  
3.axios  
4.vue-router  

还有其他一些琐碎的技术就不一一列举了。  

## 快速部署

1.clone项目到本地```git@github.com:lenve/vhr.git```  



## 文档

文档是对项目开发过程中遇到的一些问题的详细记录，主要是为了帮助没有基础的小伙伴快速理解这个项目。  

1.[权限数据库设计]()  
2.[服务端环境搭建]()  
3.[动态处理角色和资源的关系]()  
4.[密码加密并加盐]()  
5.[服务端异常的统一处理]()  
6.[axios请求封装,请求异常统一处理]()  
7.[登录成功后动态加载组件]()  
8.[角色资源关系管理]()  
9.[用户角色关系管理]()  