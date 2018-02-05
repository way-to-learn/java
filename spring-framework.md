https://spring.io/guides/tutorials/react-and-spring-data-rest/
https://start.spring.io/

Mình đang đọc về Spring Bean, tự hỏi nó khác gì so với Java Bean \
https://stackoverflow.com/questions/21866571/difference-between-javabean-and-spring-bean
https://www.tutorialspoint.com/spring/spring_bean_definition.htm
Sau khi đọc bài trên ta co thể tổng kết lại:
**Java Beans have the following rules:**\
```java
public class ThisIsJavaBean {

    //1. Default constructor
    public ThisIsJavaBean() {
    }

    private String attr;
    //2. Has at least one get/set method
    public String getAttr() {
        return this.attr;
    }
    public void setAttr(String value) {
        this.attr = value;
    }
}
```

**Spring Beans have the following rules:**\
```java

```
How to config Spring projects: \
https://stackoverflow.com/questions/8198312/servlet-mapping-using-web-xml
https://www.ibm.com/developerworks/library/ws-springjava/index.html
What class should be considered?
`@Configuration`
`@Bean`
Implementing bean lifecycle callbacks and scope?


https://stackoverflow.com/questions/13533700/maven-dependency-spring-web-vs-spring-webmvc
##AOP

```java
public interface AopProxyFactory
public interface AopProxy
public interface AopInfrastructureBean

public abstract class AopContext
public abstract class AopProxyUtils
public class AopConfigException extends NestedRuntimeException {}
public abstract class AopUtils
public abstract class AopConfigUtils
public class AopNamespaceHandler extends NamespaceHandlerSupport {}
public abstract class AopNamespaceUtils
public class AopInvocationException extends NestedRuntimeException {}
private static class AopAutoProxyConfigurer
```


Mình cần code chạy riêng cho 3 môi trường: Local, Staging, Live
Vậy sẽ có `runtime-environment`


```java
@Configuration
@EnableSwagger2
public class SwaggerConfiguration
```

-------------------
Một số điều còn mơ hồ
Servlet là gì?
Làm sao để xây dựng Web app
