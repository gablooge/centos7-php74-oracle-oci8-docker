## PHP7.4 & ORACLE OCI 8 on Centos 7 Docker
> git clone https://github.com/gablooge/centos7-php74-oracle-oci8-docker.git

> cd centos7-php74-oracle-oci8-docker

- Build image dan jalankan container pada background
> docker-compose up -d --build

- Cek container
> docker ps

- Masuk ke centos container system
> docker exec -it dms_app /bin/bash
