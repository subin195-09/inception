# 42_inception

#### _for 42Seoul_subject_

<br/>
  
  <div align="center">
  
  </div>
</div>



<br/>

## ๐ How To Run
```shell
make
```
๊ตฌ๋ ํ https://localhost ๋ก ์ ์ํ๋ฉด๋ฉ๋๋ค.

<br />

## ๐ Directory 

#### src - docker-compose ์ค์  ํ์ผ
#### src/requirements - ๊ฐ ์ปจํ์ด๋์ ๋ํ ์ค์  ๋ฐ ํ์ํ ํ์ผ๋ค
#### wiki - ๊ธฐ๋ก


<br />


## ๐บ๏ธ Overview
docker๋ฅผ ์ฌ์ฉํ์ฌ ์ฌ๋ฌ ์ปจํ์ด๋๋ฅผ ๊ตฌ์ฑํ๊ณ , docker-compose๋ฅผ ํตํด ์ปจํ์ด๋๋ค์ ๊ด๋ฆฌํฉ๋๋ค.

<br/>


## ๐งฐ Tech

<code>
    <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" height="48" alt="docker"/>
    <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" height="48" alt="nginx"/>
    <img src="https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white" height="48" alt="nginx"/>
</code>

  
<br/>
<br/>
<br/>



## ๐ Detail

- dockerFile ์์ฑ ๋ฐ container ๊ตฌํ
- Nginx, mariaDB, wordpress ์ปจํ์ด๋๋ฅผ ๊ตฌ๋์์ผ docker-compose๋ก ๊ด๋ฆฌ ํฉ๋๋ค. 
- wordpress ๊ตฌ๋์ ์ํ PHP-FPM (Fast CGI) ์ฐ๋
- HTTPS(443) ์ ์ํ OpenSSL์ ์์ฉํ TLS ์ธ์ฆ์ ๋ฐ๊ธ

<br/>
