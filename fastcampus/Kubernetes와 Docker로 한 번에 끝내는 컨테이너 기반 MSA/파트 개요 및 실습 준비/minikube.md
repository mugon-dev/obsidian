# minikube
- 가상환경을 사용하여 쿠버네티스 클러스터 구현
- 드라이버를 선택하여 원하는 가상환경에서 구성 가능

[minikube start link](https://minikube.sigs.k8s.io/docs/start/)

# 쿠버네티스 클러스터 구성
```shell
minikube start -drive=docker
```

## minikube config
![[Pasted image 20220729174144.png]]
cluster : 접속한  클러스터 정보
users : 인증 사용자 정보
context : 클러스터와 유저를 통해 인증리스트 생성