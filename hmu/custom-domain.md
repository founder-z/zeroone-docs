# Custom domain

Here we will give example setting a custom domain

For this example we will use project name as `zeroone-enterprice` and AWS Route 53.



1. Go to AWS Route 53 and setup CNAME record. Record name = enterprise, Value = [zeroone-enterprise.app.thezeroone.io](http://zeroone-enterprise.app.thezeroone.io)&#x20;

![](<../.gitbook/assets/image (10).png>)

2\. Check and remove all conflicting NS and  A records for your domain

3\. Wait for dns to be updated (you can use this [link](https://dnschecker.org/#CNAME/enterprise.zeroone.today/zeroone-enterprise.app.thezeroone.io) to check it, dont forget to switch from "exact match" operator to "contains")

4\. Setup custom domain in General tab of Settings and press `Save settings` button.

![](<../.gitbook/assets/image (14).png>)

5\. Wait for 5-10 minutes for new configuration to apply.

&#x20;
