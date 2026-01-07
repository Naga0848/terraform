### In this repo we will understand how terraform functions 


we can execute the terraform commands, if we have the .tf files

![alt text](images/terraform.png)

Once, if we write a provider.tf file and do perform a terraform init command it will start creating the files shown in the above image like LICENSE.txt  , .terraform  ,  .terraform.lock.hcl  etc which will have all the details about the terraform its provider version etc

https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources  >> is the link from where we can create the resources

if you are creating a resource, it gives us o/p using this we can create other resources. So, we use its id and create the other resources