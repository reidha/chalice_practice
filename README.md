# chalice_practice

https://pypi.org/project/chalice/

## AWS configurations

```
$ vim ~/.aws/config

[default]
region = ap-northeast-1
output = json

[profile test]
region = cn-northwest-1
output = json
```

```
$ vim ~/.aws/credentials

[default]
aws_access_key_id = {{ACCESS_KEY}}
aws_secret_access_key = {{SECRET_ACCESS_KEY}}

[test]
aws_access_key_id = {{ACCESS_KEY}}
aws_secret_access_key = {{SECRET_ACCESS_KEY}}                      
```

```
# Check the current configurations
$ aws configure list

# Edit the current configurations
$ aws configure

# Check available profiles
$ aws configure list-profiles

# Switch profiles
$ export AWS_PROFILE={{PROFILE_NAME}}
```
