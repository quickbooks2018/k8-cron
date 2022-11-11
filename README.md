
- Helm Commands to create a job

helm upgrade --install clougeeks-cron ./ -f values.yaml --namespace mycron --create-namespace

helm install clougeeks-cron ./ -f values.yaml --namespace mycron --create-namespace --debug --dry-run

helm install clougeeks-cron ./ -f values.yaml --namespace mycron --create-namespace

kubectl get cronjob -n mycron

kubectl get job -n mycron

kubectl get events -n mycron

kubectl logs pod/cloudgeeks-27802545-rz4fl -n mycron

- https://github.com/quickbooks2018/aws/blob/master/helm-useful-commands
