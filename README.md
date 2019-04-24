# sonarqube-px

This repo installs sonarqube on k8s, backed by portworx volumes for data persistence

## To install
```
git clone https://github.com/satchpx/sonarqube-px.git
cd sonarqube-px
helm install --name sonarqube sonarqube
```


#### Credits: https://github.com/helm/charts/tree/master/stable/sonarqube
