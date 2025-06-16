
Run deploy with ansible

```shell
ansible-playbook airflow-deploy.yaml \
  -i inventory/dev \
  -e target_hosts=airflow2
```