# SonarCube on K8s

```bash
helm repo add oteemocharts https://oteemo.github.io/charts

helm template sonarqube oteemocharts/sonarqube -f sonarqube-values.yaml
helm upgrade sonarqube oteemocharts/sonarqube -f sonarqube-values.yaml --install


```