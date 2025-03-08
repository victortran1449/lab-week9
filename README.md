# lab-week9
To build image (in the packer dir):
- packer init .
- packer fmt .
- packer validate .
- packer build .

To start instance (in the terraform dir):
- terraform init
- terraform fmt
- terraforn validate
- terraform plan -out lab9
- terraform apply lab9
