刚刚学学了SSM，SpringMVC + Spring + MyBatis，
Spring是开源框架，是轻量级的IoC和AOP的容器框架，主要是针对javaBean的生命周期进行管理的轻量级容器。
1）IoC(Inversion of Control)控制反转，在spring中BeanFacotory是IoC容器的核心接口，负责实例化，定位，配置应用程序中的对象及建立
这些对象间的依赖。XmlBeanFacotory实现BeanFactory接口，通过获取xml配置文件数据，组成应用对象及对象间的依赖关系。Spring中有三种注
入方式，一是setter注入，二是接口注入，三是构造方法注入。 
2）AOP面向切面编程 
