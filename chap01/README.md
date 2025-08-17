# Chap. 01 네트워크 프로그래밍과 소켓의 이해

컴파일
```
gcc hello_server.c -o hserver
```

실행
```
./hserver 9190
```

컴파일
```
gcc hello_client.c -o hclient
```

실행
```
./hclient 127.0.0.0 9190
```

컴파일
```
gcc low_open.c -o lopen
```

실행
```
./lopen
cat ./data.txt
```

컴파일
```
gcc low_read.c -o lread
```

실행
```
./lread
```

컴파일
```
gcc fd_seri.c -o fds
```

실행
```
./fds
```