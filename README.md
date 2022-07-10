# 42_inception

#### _for 42Seoul_subject_

<br/>
  
  <div align="center">
  
  </div>
</div>



<br/>

## 👟 How To Run
```shell
make
```
구동 후 https://localhost 로 접속하면됩니다.

<br />

## 🗂 Directory 

#### src - docker-compose 설정 파일
#### src/requirements - 각 컨테이너에 대한 설정 및 필요한 파일들
#### wiki - 기록


<br />


## 🗺️ Overview
docker를 사용하여 여러 컨테이너를 구성하고, docker-compose를 통해 컨테이너들을 관리합니다.

<br/>


## 🧰 Tech

<code>
    <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" height="48" alt="docker"/>
    <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" height="48" alt="nginx"/>
    <img src="https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white" height="48" alt="nginx"/>
</code>

  
<br/>
<br/>
<br/>



## 🔑 Detail

- dockerFile 작성 및 container 구현
- Nginx, mariaDB, wordpress 컨테이너를 구동시켜 docker-compose로 관리 합니다. 
- wordpress 구동을 위한 PHP-FPM (Fast CGI) 연동
- HTTPS(443) 을 위한 OpenSSL을 아용한 TLS 인증서 발급

<br/>
