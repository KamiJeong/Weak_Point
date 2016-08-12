# Regular Expressions
http://pupustory.tistory.com/132

# Encoding Problem...

- check eclipse project encoding...

- if get type is problem, check tomcat server.xml 
<Connector connectionTimeout="20000" port="8980" protocol="HTTP/1.1" redirectPort="8443" URIEncoding="UTF-8"/>
<Connector port="8909" protocol="AJP/1.3" redirectPort="8443" URIEncoding="UTF-8"/>
- if post type is problem, check web.xml
|<filter>
|  <filter-name>encodingFilter</filter-name>
|  <filter-class>org.springframework.web.filter.CharacterEncodingFilter</filter-class>
|  <init-param>
|    <param-name>encoding</param-name>
|    <param-value>utf-8</param-value>
|  </init-param>
|</filter>
|<filter-mapping>
|  <filter-name>encodingFilter</filter-name>
|  <url-pattern>*.do</url-pattern>
|</filter-mapping>

# Java 
If use Same Object type List, Can add List without overlap when i use hash array....

# Spring Framework Setting

web.xml Setting

Application Context Setting [applicationContext.xml]

dispatcher-servlet.xml Setting

# Mybatis Setting

mybatis-config.xml Setting

mapper...Setting

# Angular JS

service... ex) this.createExample = function(employee){ return $http.get() }

Must Input this code for material design lite 
// javascript code for material design lite
        angular.element(document).ready(
            function () {
                componentHandler.upgradeAllRegistered();
            });
