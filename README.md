# aws-appflow-veeva-vault-to-s3-playground

[AWS AppFlow](https://aws.amazon.com/appflow/) example of Veeva Vault data -> AppFlow -> S3.

## Notes

* no events from Vault.  only poll / query existing data manually or via trigger.
* at the time (2020-09-08) EventBridge was not available as a destination.
  * available targets: redhsift, s3, saelsforce

## Screenshot Tour

veeva vault org

![](https://www.evernote.com/l/AAGxHwv8cW9MeIDr3Cz9Duqg7wr5Oj6ukrkB/image.png)


veeva vault connection

![](https://www.evernote.com/l/AAHRq_vW-vNLlIsvbObynfHTqtZdZz1Q1gAB/image.png)

source -> destination

![](https://www.evernote.com/l/AAFCvNEVU0BN-YZKQZibgPJBqJzrMcfs0LEB/image.png)

mapping

![](https://www.evernote.com/l/AAFUFvxxDcVJJLSOtBohXBcELSRI6VQrC7cB/image.png)

![](https://www.evernote.com/l/AAGCQd2v2sVAe4sOxBweWzz-O6iZdj93ENYB/image.png)

created

![](https://www.evernote.com/l/AAHfQEEVKGFNVbg_ir7aBoxYBVwjhYcpDZkB/image.png)


run history

![](https://www.evernote.com/l/AAEW45w_DDJIgbJm_ucY-uMGAxoohGZ8AwwB/image.png)

data landed in s3

![](https://www.evernote.com/l/AAE_dm6okTFHs6TCPnRfFcmAdBo-yIVHs7YB/image.png)

![](https://www.evernote.com/l/AAFejlfQEE1J1LfEmGJ-hra2Tn3FRWgKzVsB/image.png)

## Resources

* [AppFlow Saas Applications | Veeva Vault](https://aws.amazon.com/appflow/integrations/#Veeva)
* [https://developer.veevavault.com/](https://developer.veevavault.com/)