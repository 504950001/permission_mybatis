# permission_mybatis


[http://www.jianshu.com/p/5124eef40bf0]

#### 需要修改配置的文件
    
    - *.xml 和 jdbc.properties 文件


#### 通过java类生成 mybatis-generator 下相关文件
1.生成类

   - http://www.mybatis.org/generator/running/runningWithJava.html

2.generatorConfig.xml 文件
   - http://www.mybatis.org/generator/configreference/xmlconfig.html（官方）
   - http://www.jianshu.com/p/e09d2370b796 （网友翻译版）
   
#### 如果用maven插件  

    mvn mybatis-generator:generate