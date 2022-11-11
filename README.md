
- Helm Commands to create a job

helm install clougeeks-cron ./ -f values.yaml --namespace mycron --create-namespace --debug --dry-run

helm install clougeeks-cron ./ -f values.yaml --namespace mycron --create-namespace

kubectl get cronjob -n mycron

kubectl get job -n mycron

kubectl get pods --selector=cloudgeeks -n mycron

kubectl logs pods/pod-name-from-above-command -n mycron

- https://github.com/quickbooks2018/aws/blob/master/helm-useful-commands