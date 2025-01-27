# oci-quickstart-fortinet

These are Terraform modules that deploy Fortinet on Oracle Cloud Infrastructure (OCI). They are developed jointly by Fortinet and Oracle.  These are a work in progress.

## Prerequisites
First off you'll need to do some pre deploy setup.  That's all detailed [here](https://github.com/oracle/oci-quickstart-prerequisites).

## Clone the Module
Now, you'll want a local copy of this repo by running:

    git clone https://github.com/oracle/oci-quickstart-fortinet.git

## Deploy
The TF templates here can be deployed by running the following commands:
```
cd oci-quickstart-fortinet/simple
terraform init
terraform plan
terraform apply # will prompt to continue
```

The output of `terraform apply` should look like:
```
Apply complete! Resources: 8 added, 0 changed, 0 destroyed.

Outputs:
...
```
