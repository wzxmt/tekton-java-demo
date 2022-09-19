## 创建镜像k8s拉取凭证

kubectl create secret docker-registry docker-registry \
--namespace=default \
--docker-server=https://registry.wzxmt.com \
--docker-username=admin \
--docker-password=admin
