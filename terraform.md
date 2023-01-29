---
title: Terraform
layout: default
nav_order: 2
---

[Github Repo](https://github.com/pennyberry/Public/tree/main/terraform){: .btn }

You probably will want to install some pre-requisite programs before you get going here. I suggest starting with installing Windows Subsystem for Linux and running some of the installations here: [Configuring Your Local Machine]

Once you have your machine ready, then get setup with a service principal in Azure. Create yourself an app registration and take note of the app ID and create a secret for yourself.

With the azure cli installed along with terraform, logon to azure, then you can start running your terraform code.

I like to create a shell script on my machine so it's easy to logon:

```
az login --service-principal -u <ENTER-SPN-ID-HERE> -p <ENTERPASSWORD> --tenant <ENTER-TENANT-ID>
export ARM_CLIENT_ID=<ENTER-SPN-ID-HERE>
export ARM_CLIENT_SECRET=<ENTER-PASSWORD>
export ARM_TENANT_ID=<ENTER-TENANT-ID>
export ARM_SUBSCRIPTION_ID=<ENTER-SUBSCRIPTION-ID>
```

----

[Terraform]: https://github.com/pennyberry/Public/tree/main/terraform
[Configuring Your Local Machine]: https://github.com/pennyberry/Public/tree/main/local_machine_config_scripts
[Azure CLI Scripts]: https://github.com/pennyberry/Public/tree/main/azure_cli
[pennyberry1@gmail.com]: pennyberry1@gmail.com
[Instagram]: https://www.instagram.com/tallkidssuck/
[Github]: https://github.com/pennyberry