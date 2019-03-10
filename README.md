# spring-cloud-config-example


naresh@HP MINGW64 ~/Desktop/perm/RFE
$ curl -X POST  http://localhost:8888/encrypt  -H 'Content-Type: text/plain'  -H 'Postman-Token: bf516f13-ad7e-4d76-8811-a8937fc83bd4' -H 'cache-control: no-cache' -d shlok
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    69  100    64  100     5   4266    333 --:--:-- --:--:-- --:--:--  460016a60e0a51e0a6199d3255d3856f246abbea76e2401c937f35bf02230c891a25

naresh@HP MINGW64 ~/Desktop/perm/RFE
$ curl -X POST http://localhost:8888/decrypt -H 'Content-Type: text/plain' -H 'Postman-Token: 06405c8d-eaea-42b4-9f6e-850571252317' -H 'cache-control: no-cache' -d 10267628d9c8b5b887de00f3f68f578e30080092ced0caf2948f903631ea11d4
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    69  100     5  100    64    312   4000 --:--:-- --:--:-- --:--:--  4312shlok

naresh@HP MINGW64 ~/Desktop/perm/RFE
$ curl -X POST http://localhost:8888/encrypt -H 'Content-Type: text/plain' -H 'Postman-Token: 4329d226-9c1a-4836-be21-17a1f2326b81' -H 'cache-control: no-cache' -d shlok
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    69  100    64  100     5   4266    333 --:--:-- --:--:-- --:--:--  4600311a46775d2f2e781b5d33a10eee47597c362ed8f2f419ede543a4de3b26aa78

