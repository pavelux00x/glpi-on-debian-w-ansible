sudo ansible-playbook main.yml  -i inventory.yml  --vault-id password_sql@prompt --vault-id password_user@prompt

1) You must create two ansible vaults ->  ansible-vault create **password_user** ansible-vault create **password_sql**
2) You must update the passwords.yml file putting your vault code inside it


