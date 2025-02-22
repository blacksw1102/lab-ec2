# SSH 원격 접속

## putty로 접속

pem 키로 ppk 키를 생성한다. (PuTTYgen을 이용하자.)

![alt text](20250218_111733.png)

host, port 및 ppk로 원격 접속을 시도한다.

![alt text](20250218_113026.png)

![alt text](20250218_111821.png)

![alt text](20250218_111928.png)

## ssh 명령어로 접속

pem 키의 권한 남용 여부를 체크한다. (권한 남용은 원격 접속 시 보안 정책에 제한될 수 있다.)

![alt text](20250218_112037.png)

ssh 명령어로 원격 접속을 시도한다.

```
ssh -i pem username@host
```

![alt text](20250218_112139.png)

![alt text](20250218_112210.png)