# ansible-role-amplify
Role to install Nginx Amplify agent (ubuntu/debian)

## Dependencies
run `ansible-galaxy install -r {role_file} -p {role_path}`

## Variables:

```yaml
# Required
amplify_api_key: your_api_key 
amplify_monitoring_password: amplify_monitoring_mysql_password
mysql_root_password: root_database_password

# Optional
amplify_script_dest_path: /dest/folder # (default: /tmp/)
amplify_monitoring_username: amplify_monitoring_mysql_user # (default: amplify)
mysql_host: hostname_of_database # (default: localhost)
mysql_root_user: root_database_user # (default: root)
```
