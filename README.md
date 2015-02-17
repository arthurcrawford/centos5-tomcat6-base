# centos5-tomcat6-base

Image based on CentOS_5.11.  Installs:

* Sun Java SDK 1.5.0_22
* Apache Ant 1.6.5
* Apache Tomcat 6.0.35

Installations are from the downloaded files rather than CentOS distributions.

Environment
------------

CentOS

    # cat /etc/redhat-release 
    CentOS release 5.11 (Final)

Installation directory: /opt

JAVA_HOME = /opt/jdk1.5.0_22

    # java -version
    java version "1.5.0_22"
    Java(TM) 2 Runtime Environment, Standard Edition (build 1.5.0_22-b03)
    Java HotSpot(TM) 64-Bit Server VM (build 1.5.0_22-b03, mixed mode)

ANT_HOME = /opt/apache-ant-1.6.5

    # ant -version
    Apache Ant version 1.6.5 compiled on June 2 2005

CATALINA_HOME = /opt/apache-tomcat-6.0.35

    # catalina.sh version
    Using CATALINA_BASE:   /opt/apache-tomcat-6.0.35
    Using CATALINA_HOME:   /opt/apache-tomcat-6.0.35
    Using CATALINA_TMPDIR: /opt/apache-tomcat-6.0.35/temp
    Using JRE_HOME:        /opt/jdk1.5.0_22
    Using CLASSPATH:       /opt/apache-tomcat-6.0.35/bin/bootstrap.jar
    Server version: Apache Tomcat/6.0.35
    Server built:   Nov 28 2011 11:20:06
    Server number:  6.0.35.0
    OS Name:        Linux
    OS Version:     3.16.7-tinycore64
    Architecture:   amd64
    JVM Version:    1.5.0_22-b03
    JVM Vendor:     Sun Microsystems Inc.



