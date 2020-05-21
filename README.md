# Terraform
Contoh simpel dari Terraform (Infrasucture as a code)

Sebelum memulai menggunakan Terraform, kita harus melakukan download file terraform yang dapat didownload dari link : https://www.terraform.io/downloads.html
Silahkan pilih Sistem Operasi yang anda gunakan. Dalam hal ini, saya menggunakan sistem operasi linux dengan distro debian pada amazon web service

Sebelum menggunakan terraform ada beberapa yang harus di configurasi seperti :
1. credential IAM
2. install awscli dengan command : sudo apt-get install awscli
3. set config aws cli dengan command "aws configure"
   Maka akan diminta beberapa data seperti:
	a. AWS Access Key ID :
	b. AWS Secret Access Key :
	c. Default region name :
	d. Default output format : (bisa diisi dengan json atau dikosongkan atau langsung tekan enter)
   isi file config tersebut terdapat pada path : $HOME/.aws
