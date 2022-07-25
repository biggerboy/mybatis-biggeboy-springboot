# mybatis-biggerboy-springboot

写一个自己的springboot stater，快速理解springboot的自动配置。

该项目是一个简易版的，仅供学习参考（可能会慢慢完善），生产项目请用mybatis官方的starter。

从mybatis的stater开始起步，mybatis整合spring时需要添加mybatis的依赖，mybatis-spring的依赖，仅需要配置SqlSessionFactory和SqlSessionTemplate.

如果纯注解的形式使用mybatis的话，还需要额外配置Mapper的扫描器，用于发现@Mapper注解。
