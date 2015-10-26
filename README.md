## rundeck-aws_sns-notification-plugin

### build

Run `gradle build`.

```sh
% cd AwsSnsNotificationPlugin 
% gradle build 
```

### Install

Copy the jar file to the plugins directory: 

```
% sudo cp -i build/libs/AwsSnsNotificationPlugin-0.0.1.jar  /var/lib/rundeck/libext/
```

### Configure

![](https://raw.githubusercontent.com/inokappa/rundeck-aws_sns-notification-plugin/master/doc/images/2015102602.png)

- AWS Access Key
- AWS Secret Key
- AWS Region
- AWS SNS Topic ARN
