# MY HELM CHART

## 설명
이 Chart는 테스트용 차트, 사전에 metallb 설치 필수

## 설치 방법
```bash
helm repo add myrepo1 https://xxoznge.github.io/HelmChart
helm install myrelease1 myrepo1/nginx-chart

or 

helm install myrelease1 myrepo1/nginx-chart --set replicaCount=8 
