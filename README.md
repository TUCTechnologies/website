# website
New Website for TUC Technologies

The CloudFormation template deploys an Amazon EC2 instance and an Amazon RDS MySQL database instance.

While this template is free to use, it deploys resources within Amazon Web Services and you may incur costs from there.

The template's parameters are:
* **KeyName** - Name of EC2 private key used to SSH in
* **InstanceType** - size of EC2 instance
* **SSHLocation** - network in CIDR form where SSH can be used from
* **DBName** - name of the database
* **DBUser** - username for the database
* **DBPassword** - password for the database
* **DBRootPassword** - root password for the database
* **MultiAZDatabase** - whether or not the database spans availability zones
* **DBAllocatedStorage** - amount of storage in GBs for the database
* **CertificatePFXURL** - URL where PFX encrypted certificate can be retrieved
* **CertificatePFXPassword** - password to perform decryption of PFX encrypted certificate
* **WebsiteHostname** - fully qualified domain name where the website can be reached
