 ## spring-cloud-fusion
  Spring Cloud 跨服务数据聚合框架
  
 ## 解决问题
  解决Spring Cloud服务拆分后分页数据的属性或单个对象的属性拆分之痛,
  支持对静态数据属性(数据字典)、动态主键数据进行自动注入和转化, 其中聚合的静态数据会进行`一级混存`(guava).
  
 ## 项目开发规范
 ### 包名规范
    cn.springcloud.fusion
  
 ### 应用场景：
  两个服务，A服务的某张表用到了B服务的某张表的值，我们在对A服务那张表查询的时候，把B服务某张表的值聚合在A服务的那次查询过程中
  
 ### 参考
 https://github.com/wxiaoqi/ace-merge
 
