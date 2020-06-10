
# tip

由于整个项目功能比较多，也比较复杂，因此分多期开发，目前权限管理模块已经开发完成，其他模块还在开发当中。考虑到权限管理模块相对独立，和其他模块的功能并不冲突，同时前后端分离之后的权限管理又是许多小伙伴的痛点，因此将本项目提前开源供小伙伴们研究。**但是小伙伴们需要注意的是，这个项目中你无法看到所有的功能，因为没有完工。权限管理相关的模块主要有两个，分别是  [系统管理->基础信息设置->权限组]  可以管理角色和资源的关系， [系统管理->操作员管理]  可以管理用户和角色的关系。另外，本项目也在不断的更新中，小伙伴们可以通过下方的更新记录查看最新完成的功能。**  

# 英雄帖

该项目还有一些功能尚未完成，非常欢迎小伙伴们提交pr，我会将大家所做的工作展示在README中！

# 整体效果

首先，不同的用户在登录成功之后，根据不同的角色，会看到不同的系统菜单，完整菜单如下：  

![p278](https://raw.githubusercontent.com/wiki/lenve/vhr/doc/p278.png)  

不同用户登录上来之后，可能看到的会有差异，如下：  

![p279](https://raw.githubusercontent.com/wiki/lenve/vhr/doc/p279.png)  

每个用户的角色是由系统管理员进行分配的，系统管理员给用户分配角色的页面如下：  

![p280](https://raw.githubusercontent.com/wiki/lenve/vhr/doc/p280.png)  

系统管理员也可以管理不同角色可以操作的资源，页面如下：  

![p281](https://raw.githubusercontent.com/wiki/lenve/vhr/doc/p281.png)  


# 技术栈

## 后端技术栈

1.SpringBoot  
2.SpringSecurity  
3.MyBatis  
4.MySQL  

## 前端技术栈

1.Vue  
2.ElementUI  
3.axios  
4.vue-router  

还有其他一些琐碎的技术就不一一列举了。  


