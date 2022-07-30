# ubunto docker, docker compose install
## 참고 링크
https://github.com/tedilabs/fastcampus-devops/tree/main/3-docker-kubernetes/env/ubuntu

## aws ubunto 준비
- t3.small
1. ssh 터미널 접속
2. cat > [install-docker.sh](https://github.com/tedilabs/fastcampus-devops/blob/main/3-docker-kubernetes/env/ubuntu/install-docker.sh "install-docker.sh")
	1. 내용 복사 붙여넣고 ctl+c로 나오기
3. chmod u+x install-docer.sh
	1. 해당 파일에 접근 권한 부여
4. ./install-docker.sh
	1. 해당 쉘 스크립트 실행
5. 같은 방식으로 docker-compose