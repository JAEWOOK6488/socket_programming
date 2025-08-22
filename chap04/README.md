# Chap. 04 TCP 기반 서버 / 클라이언트 1

컴파일
```
gcc echo_server.c -o eserver
```

실행
```
./eserver 9190
```

컴파일
```
gcc echo_client.c -o eclient
```

실행
```
./eclient 127.0.0.1 9190
```