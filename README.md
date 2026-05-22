Note: In windows, we didn't have ansible vault command. We will create in Linux the ansible vault and use in Windows at gitbash.

# 4.8.expense-ansible-roles-common-component-vault

```
terraform init -reconfigure
```

```
terraform plan
```

```
terraform apply -auto-approve
```

```
terraform destroy -auto-approve
```

# Login into mysql server and troubleshoot the data.
```
mysql -h db.lithesh.shop -u root -pExpenseApp@1
```

```
use transactions;
```

```
select * from transactions;
```