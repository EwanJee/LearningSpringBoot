# LearningSpringBoot

This is the repository to store JAVA codes which I have learned with via UDEMY.

Followings are descriptions per each package inside 'SpringBoot/src/main/java/com/Learning/SpringBoot/' folder.

Structures of proj1 

      >> game (folder)
      
      |_ hellospring (folder)
      
      |_ App01GamingBasicJava.java
      
      |_ App02GamingConfiguration.java
      
      |_ App03GamingSpringBeans.java
      
      |_ SpringBeanVSJavaBean.java

- JAVA sources inside "game" folder explains how good is JAVA for loose-coupling.
- App02GamingConfiguration.java lets us know how to set spring beans in a JAVA class using some annotations such as @Configuration, @Bean.

      ***                   What I have learned from this proj1
  
          Spring Container (= Spring Context, IOC Container) : Manages Spring beans and their lifecycle.
          Application Context : Easy to use in web applications and easy to integrate with SPRING AOP (Aspect Oriented Programming).
          Bean Factory : Basic Spring Container
          Java Bean : Has public default constructors, Allow access to their properties using getter and setter, implement hava.io.Serializable
          POJO : Plain Old Java Object. Any java object is a POJO
          Spring Bean : Any Java object that is managed by Spring. Spring uses IOC Conatiner to manage these beans.
          If multiple matching beans have been found, we can choose between @Qualifier and @Primary.
                                                                                                        ***

proj2 : 
