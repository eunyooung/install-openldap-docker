# Openldap

## 실행
```
docker-compose up -d
```

## 테스트
```
docker exec openldap ldapsearch -x -H ldap://localhost -b dc=ey,dc=com -D "cn=admin,dc=ey,dc=com" -w admin
```

## 접속
https://localhost:6443