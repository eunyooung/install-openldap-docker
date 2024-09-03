# Openldap

```
docker-compose up -d
```

```
docker exec openldap ldapsearch -x -H ldap://localhost -b dc=ey,dc=com -D "cn=admin,dc=ey,dc=com" -w admin
```

