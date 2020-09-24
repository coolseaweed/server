# 자주쓰는 터미널 명령어 정리


  [1. screen](#1.-screen)

  [2. find](#2.-find)


## 1. screen <a name="1.-screen"></a>

|Commands|Function|
|:----|:----|
|screen -S [name]|[name] 으로 screen 생성|
|screen -ls|현재 생성된 screen list |
|screen -r [name]|deatach 되어 있는 screen attach|
|screen -X -S [name] kill|[name]screen 삭제|
|screen -r d|sreen 강제로 detach|
|Ctrl+a+d|screen deatch 단축키|


---

## 2. find <a name="2.-find"></a>

  ```
  $ find . -name "*.lst"
  ```

---

## 3. dd <a name="2.-dd"></a>
> File read write 속도 측정에 사용되는 커맨드

  ```
  $ sudo dd if=/dev/zero of=/test/bb  bs=1M count=1024 oflag=direct
  ```
  [ ! ] /test/bb 에 실제 용량이 써지므로 테스트 후 





