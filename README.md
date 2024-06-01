### 애플실리콘 MAC 우분투 가상 머신 프로비저닝

### 순서

```plainText
1. VMware Fusion 설치
2. brew install hashicorp/tap/hashicorp-vagrant
3. Vagrant Vmware Utility 설치
4. 시스템 재기동
```

### 명령어

```sh
# 가상 머신 상태 조회
sudo vagrant status
# 가상 머신 시작
sudo vagrant up
# 가상 머신 종료
sudo vagrant halt
# ssh 접속
sudo vagrant ssh 서버이름
```

### 참고 링크

https://devopscube.com/build-vms-mac-silicon-with-vagrant/
