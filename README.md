```
export AWS_SECRET_ACCESS_KEY=
export AWS_ACCESS_KEY_ID=
```

`config/`に　
serverアクセス用の`authorized_key`
github用の`id_rsa`
を置いておく

### ec2
```
ansible-playbook -i hosts/aws/ec2.py aws.yml --private-key=xxxxxxx
```

```
ansible-playbook -i hosts/ec2-servers  ec2-server.yml --private-key=xxxxxxx
```
