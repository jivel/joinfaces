JSF Spring Boot Starter
=============================
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.persapiens/jsf-spring-boot-starter/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.persapiens/jsf-spring-boot-starter)
[![Build Status](https://travis-ci.org/persapiens/jsf-spring-boot-starter.svg?branch=master)](https://travis-ci.org/persapiens/jsf-spring-boot-starter)
[![Coverage Status](https://coveralls.io/repos/github/persapiens/jsf-spring-boot-starter/badge.svg?branch=master)](https://coveralls.io/github/persapiens/jsf-spring-boot-starter?branch=master)
[![Dependency Status](https://www.versioneye.com/user/projects/573daf0bce8d0e004505e961/badge.svg?style=flat)](https://www.versioneye.com/user/projects/573daf0bce8d0e004505e961)
[![Javadocs](http://javadoc.io/badge/com.github.persapiens/jsf-spring-boot-parent.svg)](http://javadoc.io/doc/com.github.persapiens/jsf-spring-boot-parent)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

This project enables [JSF](http://www.oracle.com/technetwork/java/javaee/javaserverfaces-139869.html) usage inside JAR packaged [Spring Boot](http://projects.spring.io/spring-boot/) Application. 

It autoconfigures [PrimeFaces](http://primefaces.org/), [BootsFaces](http://bootsfaces.net/), [OmniFaces](http://omnifaces.org/), [AngularFaces](http://angularfaces.com/), [Mojarra](https://javaserverfaces.java.net/) and [MyFaces](http://myfaces.apache.org/) libraries to run at embedded [Tomcat](http://tomcat.apache.org/), [Jetty](http://www.eclipse.org/jetty) or [Undertow](http://undertow.io) servlet containers.

It also aims to solve [JSF](http://www.oracle.com/technetwork/java/javaee/javaserverfaces-139869.html) and [Spring Boot](http://projects.spring.io/spring-boot/) integration features. Current version includes [JSF](http://www.oracle.com/technetwork/java/javaee/javaserverfaces-139869.html) and [CDI](http://www.cdi-spec.org/) annotations support and [Spring Security](http://projects.spring.io/spring-security/) JSF Facelet Tag support.


## How to use

[Jsf Spring Boot Starter Example](https://github.com/persapiens/jsf-spring-boot-starter-example) shows JSF Spring Boot Starter usage. It may help you to choose the JSF Spring Boot Starter that fits your needs.

## Key Features

### Twelve JSF Spring Boot Starters available

Starter | Servlet Container | JSF Implementation | JSF Libraries
------------ | ------------- | ------------- | -------------
jsf-spring-boot-starter | [Tomcat](http://tomcat.apache.org/) | [Mojarra](https://javaserverfaces.java.net/) | [PrimeFaces 6.0](http://primefaces.org), [PrimeFaces Extensions 6.0.0](http://primefaces-extensions.github.io/)
jsf-bootsfaces-spring-boot-starter | [Tomcat](http://tomcat.apache.org/) | [Mojarra](https://javaserverfaces.java.net/) |  [BootsFaces 0.8.6](http://bootsfaces.net), [AngularFaces 2.1.3](http://angularfaces.com), [PrimeFaces 5.3](http://primefaces.org), [PrimeFaces Extensions 4.0.0](http://primefaces-extensions.github.io/)
jsf-myfaces-spring-boot-starter | [Tomcat](http://tomcat.apache.org/) | [MyFaces](http://myfaces.apache.org/) | [PrimeFaces 6.0](http://primefaces.org), [PrimeFaces Extensions 6.0.0](http://primefaces-extensions.github.io/)
jsf-myfaces-bootsfaces-spring-boot-starter | [Tomcat](http://tomcat.apache.org/) | [MyFaces](http://myfaces.apache.org/) | [BootsFaces 0.8.6](http://bootsfaces.net), [AngularFaces 2.1.3](http://angularfaces.com), [PrimeFaces 5.3](http://primefaces.org), [PrimeFaces Extensions 4.0.0](http://primefaces-extensions.github.io/)
jsf-jetty-spring-boot-starter | [Jetty](http://www.eclipse.org/jetty) | [Mojarra](https://javaserverfaces.java.net/) | [PrimeFaces 6.0](http://primefaces.org), [PrimeFaces Extensions 6.0.0](http://primefaces-extensions.github.io/)
jsf-jetty-bootsfaces-spring-boot-starter | [Jetty](http://www.eclipse.org/jetty) | [Mojarra](https://javaserverfaces.java.net/) | [BootsFaces 0.8.6](http://bootsfaces.net), [AngularFaces 2.1.3](http://angularfaces.com), [PrimeFaces 5.3](http://primefaces.org), [PrimeFaces Extensions 4.0.0](http://primefaces-extensions.github.io/)
jsf-jetty-myfaces-spring-boot-starter | [Jetty](http://www.eclipse.org/jetty) | [MyFaces](http://myfaces.apache.org/) | [PrimeFaces 6.0](http://primefaces.org), [PrimeFaces Extensions 6.0.0](http://primefaces-extensions.github.io/)
jsf-jetty-myfaces-bootsfaces-spring-boot-starter | [Jetty](http://www.eclipse.org/jetty) | [MyFaces](http://myfaces.apache.org/) | [BootsFaces 0.8.6](http://bootsfaces.net), [AngularFaces 2.1.3](http://angularfaces.com), [PrimeFaces 5.3](http://primefaces.org), [PrimeFaces Extensions 4.0.0](http://primefaces-extensions.github.io/)
jsf-undertow-spring-boot-starter | [Undertow](http://undertow.io) | [Mojarra](https://javaserverfaces.java.net/) | [PrimeFaces 6.0](http://primefaces.org), [PrimeFaces Extensions 6.0.0](http://primefaces-extensions.github.io/)
jsf-undertow-bootsfaces-spring-boot-starter | [Undertow](http://undertow.io) | [Mojarra](https://javaserverfaces.java.net/) | [BootsFaces 0.8.6](http://bootsfaces.net), [AngularFaces 2.1.3](http://angularfaces.com), [PrimeFaces 5.3](http://primefaces.org), [PrimeFaces Extensions 4.0.0](http://primefaces-extensions.github.io/)
jsf-undertow-myfaces-spring-boot-starter | [Undertow](http://undertow.io) | [MyFaces](http://myfaces.apache.org/) | [PrimeFaces 6.0](http://primefaces.org), [PrimeFaces Extensions 6.0.0](http://primefaces-extensions.github.io/)
jsf-undertow-myfaces-bootsfaces-spring-boot-starter | [Undertow](http://undertow.io) | [MyFaces](http://myfaces.apache.org/) | [BootsFaces 0.8.6](http://bootsfaces.net), [AngularFaces 2.1.3](http://angularfaces.com), [PrimeFaces 5.3](http://primefaces.org), [PrimeFaces Extensions 4.0.0](http://primefaces-extensions.github.io/)

Note that all starters include the following libraries

Library | Dependency | Description
------------ | ------------- | -------------
[primefaces-all-themes](http://primefaces.org/) | [1.0.8](http://search.maven.org/#artifactdetails\|org.primefaces.extensions\|all-themes\|1.0.8\|jar) | Themes for primefaces
[omnifaces](http://omnifaces.org/) | [1.13](http://search.maven.org/#artifactdetails\|org.omnifaces\|omnifaces\|1.13\|jar) | Utility library for JSF 2
[cdi-api](http://www.cdi-spec.org/) | [1.2](http://search.maven.org/#artifactdetails\|javax.enterprise\|cdi-api\|1.2\|jar) | Api of CDI (Contexts and Dependency Injection)

### JSF properties configuration via application.properties or application.yml

Library | Namespace | Example | Full Example
------------ | ------------- | --------- | ---------
standard (javax.faces) | jsf | jsf.PROJECT_STAGE: Development | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-spring-boot-autoconfigure/src/test/resources/application.yml)
[primefaces](http://primefaces.org/) | jsf.primefaces | jsf.primefaces.theme: overcast | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-primefaces-spring-boot-autoconfigure/src/test/resources/application.yml)
[bootsfaces](http://bootsfaces.net/) | jsf.bootsfaces | jsf.bootsfaces.USETHEME: true | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-bootsfaces-spring-boot-autoconfigure/src/test/resources/application.yml)
[omnifaces](http://omnifaces.org/) | jsf.omnifaces | jsf.omnifaces.FACES_VIEWS_ENABLED: true | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-omnifaces-spring-boot-autoconfigure/src/test/resources/application.yml)
[angularfaces](http://angularfaces.com/) | jsf.angularfaces | jsf.angularfaces.addLabels: true | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-angularfaces-spring-boot-autoconfigure/src/test/resources/application.yml)
[mojarra](https://javaserverfaces.java.net/) | jsf.mojarra | jsf.mojarra.preferXHTML: true | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-mojarra-spring-boot-autoconfigure/src/test/resources/application.yml)
[myfaces](http://myfaces.apache.org/) | jsf.myfaces | jsf.myfaces.PRETTY_HTML: true | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-myfaces-spring-boot-autoconfigure/src/test/resources/application.yml)
[jetty](http://www.eclipse.org/jetty) | jsf.jetty | jsf.jetty.classPathResource: META-INF/resources | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-jetty-spring-boot-autoconfigure/src/test/resources/application.yml)
[undertow](http://undertow.io) | jsf.undertow | jsf.undertow.classPathResource: META-INF/resources | [application.yml](https://github.com/persapiens/jsf-spring-boot-starter/blob/master/jsf-undertow-spring-boot-autoconfigure/src/test/resources/application.yml)

Additional information in [#22](https://github.com/persapiens/jsf-spring-boot-starter/issues/22)

### JSF and CDI annotations support automatically

Annotation |
------- | ----
[@NoneScoped](http://docs.oracle.com/javaee/7/api/javax/faces/bean/NoneScoped.html) |
[@RequestScoped](http://docs.oracle.com/javaee/7/api/javax/enterprise/context/RequestScoped.html) |
[@ViewScoped](http://docs.oracle.com/javaee/7/api/javax/faces/view/ViewScoped.html) |
[@SessionScoped](http://docs.oracle.com/javaee/7/api/javax/enterprise/context/SessionScoped.html) |
[@ApplicationScoped](http://docs.oracle.com/javaee/7/api/javax/enterprise/context/ApplicationScoped.html) |

### Spring Security JSF Facelet Tag support 

Namespace: **http://www.springframework.org/security/tags**

Tag | Description
------------ | -------------
authorize | perform Spring Security authorization decisions, using attributes: ifAnyGranted, ifAllGranted, ifNotGranted, access, url, method, var.
anonymous | verify if the user is anonymous.
authenticated | verify if the user is not anonymous.
fullyAuthenticated | verify if the is not an anonymous or a remember-me user.

Function | Description
------------ | -------------
areAllGranted | returns true if the user has all of of the given authorities.
areAnyGranted | returns true if the user has any of the given authorities.
areNotGranted | returns true if the user does not have any of the given authorities.
isAllowed | returns true if the user is allowed to access the given URL and HTTP method combination.
isAnonymous | returns true if user is anonymous.
isAuthenticated | returns true if the user is not anonymous.
isFullyAuthenticated | returns true if the is not an anonymous or a remember-me user.

Additional information in [#29](https://github.com/persapiens/jsf-spring-boot-starter/issues/29)

## System Requirements

By default, JSF Spring Boot Starter requires [Java 7](http://java.com) and [Spring Boot 1.3.5](http://projects.spring.io/spring-boot/) or above.

## Getting Help

* Report questions and bugs at [github.com/jsf-spring-boot-starter/issues](https://github.com/persapiens/jsf-spring-boot-starter/issues).

## Contributing

* Report documentation, features, enhancement and bugs at [github.com/jsf-spring-boot-starter/issues](https://github.com/persapiens/jsf-spring-boot-starter/issues).
* Pull requests are welcome.

## Structure

This software is multi module [Maven](http://maven.apache.org) project and follows [Spring Boot Reference](http://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-developing-auto-configuration.html) to create JSF Auto Configuration. See what's inside each submodule:

Submodule | Description
------------ | -------------
[jsf-spring-boot-integration](jsf-spring-boot-integration)	| Integration solutions for [JSF](http://www.oracle.com/technetwork/java/javaee/javaserverfaces-139869.html) and [Spring Boot](http://projects.spring.io/spring-boot/) like [JSF](http://www.oracle.com/technetwork/java/javaee/javaserverfaces-139869.html) and [CDI](http://www.cdi-spec.org/) annotations support and [Spring Security](http://projects.spring.io/spring-security/) JSF Facelet Tag support
[jsf-spring-boot-autoconfigure](jsf-spring-boot-autoconfigure)	| Jsf Spring Boot Autoconfiguration for Standard JavaxFaces
[jsf-mojarra-spring-boot-autoconfigure](jsf-spring-boot-autoconfigure)	| Jsf Spring Boot Autoconfiguration for [Mojarra](https://javaserverfaces.java.net/)
[jsf-myfaces-spring-boot-autoconfigure](jsf-myfaces-spring-boot-autoconfigure)	| Jsf Spring Boot AutoConfiguration for [MyFaces](http://myfaces.apache.org/)
[jsf-omnifaces-spring-boot-autoconfigure](jsf-spring-boot-autoconfigure)	| Jsf Spring Boot Autoconfiguration for [OmniFaces](http://omnifaces.org/)
[jsf-primefaces-spring-boot-autoconfigure](jsf-spring-boot-autoconfigure)	| Jsf Spring Boot Autoconfiguration for  [PrimeFaces](http://primefaces.org/)
[jsf-primefaces53-spring-boot-autoconfigure](jsf-spring-boot-autoconfigure)	| Jsf Spring Boot Autoconfiguration for  [PrimeFaces 5.3](http://primefaces.org/)
[jsf-bootsfaces-spring-boot-autoconfigure](jsf-spring-boot-autoconfigure)	| Jsf Spring Boot Autoconfiguration for  [BootsFaces](http://bootsfaces.net/)
[jsf-angularfaces-spring-boot-autoconfigure](jsf-spring-boot-autoconfigure)	| Jsf Spring Boot Autoconfiguration for  [AngularFaces](http://angularfaces.net/)
[jsf-jetty-spring-boot-autoconfigure](jsf-jetty-spring-boot-autoconfigure)	| Jsf Spring Boot AutoConfiguration for [Jetty](http://www.eclipse.org/jetty)
[jsf-jetty-myfaces-spring-boot-autoconfigure](jsf-jetty-myfaces-spring-boot-autoconfigure)	| Jsf Spring Boot AutoConfiguration for [Jetty](http://www.eclipse.org/jetty) and [MyFaces](http://myfaces.apache.org/)
[jsf-undertow-spring-boot-autoconfigure](jsf-undertow-spring-boot-autoconfigure) | Jsf Spring Boot AutoConfiguration for [Undertow](http://undertow.io)
[jsf-undertow-myfaces-spring-boot-autoconfigure](jsf-undertow-myfaces-spring-boot-autoconfigure) | Jsf Spring Boot AutoConfiguration for [Undertow](http://undertow.io) and [MyFaces](http://myfaces.apache.org/)
[jsf-spring-boot-starter](jsf-spring-boot-starter)	| Jsf Spring Boot Starter for [Tomcat](http://tomcat.apache.org/) and [Mojarra](https://javaserverfaces.java.net/) and [PrimeFaces 6.0](http://primefaces.org)
[jsf-bootsfaces-spring-boot-starter](jsf-bootsfaces-spring-boot-starter)	| Jsf Spring Boot Starter for [Tomcat](http://tomcat.apache.org/) and [Mojarra](https://javaserverfaces.java.net/) and [PrimeFaces 5.3](http://primefaces.org) and [BootsFaces](http://bootsfaces.net)
[jsf-myfaces-spring-boot-starter](jsf-myfaces-spring-boot-starter)	| Jsf Spring Boot Starter for [Tomcat](http://tomcat.apache.org/) and [MyFaces](http://myfaces.apache.org/) and [PrimeFaces 6.0](http://primefaces.org)
[jsf-myfaces-bootsfaces-spring-boot-starter](jsf-myfaces-bootsfaces-spring-boot-starter)	| Jsf Spring Boot Starter for [Tomcat](http://tomcat.apache.org/) and [MyFaces](http://myfaces.apache.org/) and [PrimeFaces 5.3](http://primefaces.org) and [BootsFaces](http://bootsfaces.net)
[jsf-jetty-spring-boot-starter](jsf-jetty-spring-boot-starter)	| Jsf Spring Boot Starter for [Jetty](http://www.eclipse.org/jetty) and [Mojarra](https://javaserverfaces.java.net/) and [PrimeFaces 6.0](http://primefaces.org)
[jsf-jetty-bootsfaces-spring-boot-starter](jsf-jetty-bootsfaces-spring-boot-starter)	| Jsf Spring Boot Starter for [Jetty](http://www.eclipse.org/jetty) and [Mojarra](https://javaserverfaces.java.net/) and [PrimeFaces 5.3](http://primefaces.org) and [BootsFaces](http://bootsfaces.net)
[jsf-jetty-myfaces-spring-boot-starter](jsf-jetty-myfaces-spring-boot-starter)	| Jsf Spring Boot Starter for [Jetty](http://www.eclipse.org/jetty) and [MyFaces](http://myfaces.apache.org/) and [PrimeFaces 6.0](http://primefaces.org)
[jsf-jetty-myfaces-bootsfaces-spring-boot-starter](jsf-jetty-myfaces-bootsfaces-spring-boot-starter)	| Jsf Spring Boot Starter for [Jetty](http://www.eclipse.org/jetty) and [MyFaces](http://myfaces.apache.org/) and [PrimeFaces 5.3](http://primefaces.org) and [BootsFaces](http://bootsfaces.net)
[jsf-undertow-spring-boot-starter](jsf-undertow-spring-boot-starter) | Jsf Spring Boot Starter for [Undertow](http://undertow.io) and [Mojarra](https://javaserverfaces.java.net/) and [PrimeFaces 6.0](http://primefaces.org)
[jsf-undertow-bootsfaces-spring-boot-starter](jsf-undertow-bootsfaces-spring-boot-starter) | Jsf Spring Boot Starter for [Undertow](http://undertow.io) and [Mojarra](https://javaserverfaces.java.net/) and [PrimeFaces 5.3](http://primefaces.org) and [BootsFaces](http://bootsfaces.net)
[jsf-undertow-myfaces-spring-boot-starter](jsf-undertow-myfaces-spring-boot-starter) | Jsf Spring Boot Starter for [Undertow](http://undertow.io) and [MyFaces](http://myfaces.apache.org/) and [PrimeFaces 6.0](http://primefaces.org)
[jsf-undertow-myfaces-bootsfaces-spring-boot-starter](jsf-undertow-myfaces-bootsfaces-spring-boot-starter) | Jsf Spring Boot Starter for [Undertow](http://undertow.io) and [MyFaces](http://myfaces.apache.org/) and [PrimeFaces 5.3](http://primefaces.org) and [BootsFaces](http://bootsfaces.net)
