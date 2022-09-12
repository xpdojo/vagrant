# 여러 개의 VM 생성

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
a3686bb  node-1 virtualbox running /home/markruler/xpdojo/vagrant/2_multiple_node 
ee85047  node-2 virtualbox running /home/markruler/xpdojo/vagrant/2_multiple_node
```

```sh
# vagrant ssh a36
vagrant ssh node-1

# vagrant ssh ee8
vagrant ssh node-2
```

## 제거

```sh
vagrant destroy --graceful --parallel
vagrant global-status --prune
```
