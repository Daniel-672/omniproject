### 리눅스 가상 들어가기
source /root/venv/camusvenv/bin/activate

### 도커 버전에 따른 설치
sudo yum install docker-engine-17.12.1.ce-1.el7.centos

### 도커로 빌드하기 뒤에 .은 dockerfile을 
sudo docker build -t camus:dev .
