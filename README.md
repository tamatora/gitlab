# 構築場所
ETS240vmh001P上のVM ETS240dev002Pに実装

# Ansible
> zabbix-agentとchronyとfirewall分を構築する
## 実行コマンド
> 構文チェック(開発環境)
```
ansible-playbook site.yml -i hosts/development --syntax-check -K -k
ansible-playbook site.yml -i hosts/development -C -K -k
```
