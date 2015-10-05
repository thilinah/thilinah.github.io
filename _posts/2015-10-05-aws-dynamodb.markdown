---
layout: post
title: Getting Started with AWS Dynamo DB
description: A Quick Getting Started Guide to AWS Dynamo DB
---

### Dynamo DB Local tool
For testing Dynamo DB the only two options available is using an AWS account to do the testing or downloading local Dynamo DB tool. The latest tool
can be downloaded from:

*<a href="http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Tools.DynamoDBLocal.html">http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Tools.DynamoDBLocal.html</a>*

For running the tool execute following command (note that you need to have JRE installed), after changing the path *'/root/DynamoDBServer/'* accordingly

(java -Djava.library.path=/root/DynamoDBServer/DynamoDBLocal_lib -jar /root/DynamoDBServer/DynamoDBLocal.jar -sharedDb &)

Usually local tool uses the port 8000. Also you can access the web application for managing the DB through following url

![AWS Local tool Shell](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/images/shell-main.png "AWS Local tool Shell")

