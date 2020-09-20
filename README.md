# AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies
AWS S3 Glacier Access Control with Vault Lock Policies

To create a new vault, navigate to the S3 Glacier console and click on Create Vault.

![alt text](https://github.com/doyle199/AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies/blob/master/Glacier.png)

Make sure you’re in a supported region. Create a name and click next step.

![alt text](https://github.com/doyle199/AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies/blob/master/vault_name.png)

For this example, we will not enable notifications. Click Next Step.

![alt text](https://github.com/doyle199/AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies/blob/master/notifications.png)

Review and click Submit.

![alt text](https://github.com/doyle199/AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies/blob/master/Submit.png)

Take note of the vault ARN in the details tab.

![alt text](https://github.com/doyle199/AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies/blob/master/Glacier_ARN.png)

To deny deletion permissions for archives less than 365 days old, Click on the vault lock Tab and then click on create vault lock policy. 

![alt text](https://github.com/doyle199/AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies/blob/master/vault_lock_1.png)

Add the following JSON to the box https://github.com/doyle199/AWS-S3-Glacier-Access-Control-with-Vault-Lock-Policies/blob/master/Initiate%20Vault%20Lock.jscsrc. Put the correct Vault ARN. Click Initiate Vault Lock.

