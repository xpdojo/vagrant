# Vagrant

- [Vagrant](#vagrant)
  - [설치](#설치)
    - [Mac OS X](#mac-os-x)
  - [명령어](#명령어)
  - [Vagrantfile](#vagrantfile)

VM을 관리하는 오픈소스 도구다.
HashiCorp에서 만들고 배포한다.
VirtualBox, Hyper-V, VMware와 같은
[provider](https://www.vagrantup.com/docs/providers)
가 별도로 필요하다.

## 설치

- [Installing Vagrant](https://www.vagrantup.com/docs/v2.3.0/installation)
- [Download Vagrant](https://www.vagrantup.com/downloads)

### Mac OS X

```sh
brew install vagrant
```

## 명령어

| command         | description        |
| --------------- | ------------------ |
| vagrant init    | Vagrantfile 생성   |
| vagrant up      | VM 생성 및 실행    |
| vagrant status  | VM 상태 확인       |
| vagrant destroy | VM 멈춤 및 제거    |
| vagrant halt    | VM 정지            |
| vagrant suspend | VM 휴면            |
| vagrant resume  | VM 휴면에서 깨우기 |
| vagrant reload  | VM 재실행          |
| vagrant ssh     | VM 접속            |

## Vagrantfile

Ruby로 작성하는 Vagrant 설정 파일이다.
