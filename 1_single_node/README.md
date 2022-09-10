# 반복문으로 동일한 VM 생성

## 생성 및 실행

```sh
# vagrant up --debug-timestamp
vagrant up
```

## 상태 확인

```sh
> vagrant global-status
id       name   provider   state   directory
--------------------------------------------------------------------------
6088cb4  node-1 virtualbox running /home/markruler/xpdojo/vagrant/1_single_node 
```

```sh
# vagrant ssh 608
vagrant ssh node-1
```

## 제거

```sh
vagrant destroy --graceful --parallel
```
