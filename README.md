# packer-ami-template

It is just a simple project to show how we can build a custom AMI using packer template. 

### Description 
HashiCorp Packer is a lightweight, open source tool for building automating machine images across multiple platforms, including AWS, Azure, and GCP. Here, we will be be building a custom AMI using Packer.

### Requirements
- IAM user with administrator access to EC2.
- [Packer](https://releases.hashicorp.com/packer/1.7.8/packer_1.7.8_linux_amd64.zip)
- Linux Operating system

### Installation
1. To install packer, run the following commands to download the package
```
$ wget https://releases.hashicorp.com/packer/1.7.8/packer_1.7.8_linux_amd64.zip
$ unzip packer_1.7.8_linux_amd64.zip
$ mv packer /usr/bin/
```
2. After installing Packer, verify the installation is working by checking that the packer is available:
```
$ packer
```
3. To check software version run:
```
$ packer --version
```


