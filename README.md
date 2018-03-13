### Before provisioning, perform these commands to setup your user and password.

`sed -i "s|REPLACE_SSH_KEY|$(cat ~/.ssh/id_rsa.pub)|g" ~/.appflow/tenant/example/development/group_vars/all`

`sed -i "s|REPLACE_USER_NAME|$(whoami)|g" ~/.appflow/tenant/example/development/group_vars/all`

`echo "test" > ~/.appflow/vault/example/development`
