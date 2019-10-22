# aws_python
 A simple example of creating instance in AWS

 ## Requirements:
 * Install [awscli](https://aws.amazon.com/ru/cli/)
 * Install [Python](https://www.python.org/)
 * Install [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/quickstart.html#installation)

 ### First steps
 * If you have the AWS CLI installed, then you can use it to configure your credentials file:
 ```
 $ aws configure
 ```

 * Alternatively, you can create the credential file yourself. By default, its location is at ~/.aws/credentials:
 ```
[default]
aws_access_key_id = YOUR_ACCESS_KEY
aws_secret_access_key = YOUR_SECRET_KEY
```
* You may also want to set a default region. This can be done in the configuration file. By default, its location is at ~/.aws/config:
```
[default]
region=us-east-1
```

* The create_key_pair.py file will create pem key for connect to your create_instances:
```
$ python create_key_pair.py
```

* The create_instance.py file will create an instance with access using the pem key created earlier:
```
$ python create_key_pair.py
```
