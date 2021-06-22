# locust docker and kubenetes

## docker

docker-entrypoint.sh -> LOCUST_MODE,LOCUST_MASTER,LOCUST_FLAGS all depends on ENV vars

## kubernetes

### master
locust-master.yaml -> service and deployment

### slaves
locust-slave.yaml -> deployment depends on master service