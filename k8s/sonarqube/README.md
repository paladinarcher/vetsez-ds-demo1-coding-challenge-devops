# Sonarqube
Instructions to install SonarQube into a Kubernetes cluster using a the [SonarQube Helm chart](https://github.com/helm/charts/tree/master/stable/sonarqube).

## Install Sonarqube with Helm by running:
 ```
 helm install -n sonar stable/sonarqube -f values.yaml
 ```