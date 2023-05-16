# Deploy-WordPress-Website-The-Traditional-Way
Resources Used - **VPC(NAT Gateway,IGW,Route Table) , Route 53, RDS,EC2,ALB, EFS**
# Architecture Of WordPress Website
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/cefd25ee-0874-44c5-b959-be75ea2a8baf)

# Output
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/1c06443a-732c-47c1-8510-7de67a3db438)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/9459884e-37d7-4835-b3ba-d8c36e29d244)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/df9307f1-a123-4915-9f82-1d30b80125f7)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/618b0d44-9ce4-472c-ae66-5db24debfdb7)


## VPC
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/9bb2a213-a8d1-491f-b7b8-52ee28b6b55a)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/d9ba4d3c-5599-4697-8887-6ea91dc0f341)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/8354bef7-2c9d-4214-a4d5-b33eddc3308b)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/27bde231-b3a4-4e95-a7bd-6b87930c80f4)

### Internet Gateway
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/fd8269f6-43cf-4c43-a63f-6136a3a4d0d0)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/e63dbe6f-2997-47a5-999b-d48871781046)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/112658da-104d-4d14-a253-6f038975dcec)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/6548e6cf-5ac8-4105-ad68-d707babf63cb)

### Subnets
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/22ae33d6-22b5-4598-b9aa-ab22df857ca1)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/7adaa994-02b1-4628-b818-0ad1963027f2)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/e44fcb72-1e81-4631-b9fc-397b6d5019b9)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/1ac88f2e-4bd3-41ca-84d8-4c2f81494c00)

### Route Table
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/6e2fa03b-0a53-485e-b8fd-f54ffee57130)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/364a1c81-9498-47f5-8353-aedc36d95aef)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/c15659a2-7977-4d84-bb8c-c87dba52fb99)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/f8f6b770-b6e7-4ece-874a-fa73d9b6d8f1)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/e92da5f0-4cdb-4647-859b-be46b95969c1)

### Subnet Associations 
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/ca55eb77-0d50-4af1-9e17-a21239d9c2d0)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/b278ebdc-38c1-47d4-ab30-30d7e6b4f988)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/bd26df86-4018-48dc-a82a-d80cc39d293a)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/478b49d2-0295-4a10-bed6-24f279dac8b6)

### NAT Gateways
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/a6d9b359-de0e-4abf-ac5c-3fd9bc386efd)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/9b397648-4375-4520-b7aa-32c97dad2bbf)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/df2d9589-114b-4199-93fb-c9bfb589888a)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/11f39b99-d309-4129-9efb-f2d1e6eb6e6a)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/84cfad25-422e-47bd-b9a7-9b47b4311dd4)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/0211e69a-398f-45b9-8b6a-eef885ee3372)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/f9c18b46-986e-4aa3-8565-23c62d72a497)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/a146f735-94e5-4896-9a1b-ced490625285)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/d9796252-34e4-4d67-9c58-a8f9680e4d2f)

## Security Groups
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/3afcd947-c9ec-42ff-8010-ab9a04a96aad)

### ALB Security Group
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/d46e0b45-e455-486c-afa9-9e639919b43e)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/bafe8d02-5156-41d8-accd-ca09bc8e0aa4)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/d0881606-da32-457e-8971-6a733a9d7603)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/5c883e0c-fe0d-423d-8eb9-fa2fa87d0a49)

### SSH Security Group
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/e1530214-1905-45a9-bcac-84b27d8e843f)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/3300fc26-6c43-4c50-83a0-e2b116c19926)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/f399c9fd-e420-4827-8622-c0f0b9388f40)

### WebServer Security Group
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/22f480df-7b5a-4f77-a4ee-ded042bc0640)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/2b464db0-0474-4956-a72d-811ab7e104ce)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/d151f659-24d9-4ca4-a4d3-39ff3fe90b3b)

### DataBase Security Group
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/5d97544e-151e-4a69-b9a1-0cdf94c72812)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/df965c97-f8ac-48e1-82bc-97ebbd75c581)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/9b1fe68c-1b31-4e80-872a-9d28baabee62)

### EFS Security Group
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/e14daa5c-93da-4000-b03b-f6c76dfbdd87)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/4453c9fb-d7f4-41a1-9901-3ae0d27d41c2)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/24ccb5c6-418f-4988-82a2-94cadc5d6eed)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/0dd1590d-028b-44fb-bf5c-76b0ee40f181)

## RDS
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/153c127b-5d20-4e52-9d01-8f2d7a3c5e8f)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/fcaf1510-fb82-48ba-aad6-632d880edb13)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/8811a223-b6f8-4129-982f-b4ab77c32a08)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/07530929-9353-48d5-8ca2-e91505be8162)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/2f32c427-da03-4525-ab38-daf4b67a6f44)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/f5c7e8b3-9eeb-40b3-bd5d-38d3b04f8af4)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/e277991e-fd89-4e31-85b3-15a6323dff09)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/bc0ff032-127c-4d30-a44a-987194144c00)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/b1aba9d8-2a6b-48fc-8d28-a75bd9d8de49)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/13e03b9b-d41f-4b7d-baf0-c3ccded81be6)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/793301f1-0181-4a14-a9df-2ed3167f525a)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/99c0fe35-f3ee-4dea-967e-56a20a2c85d5)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/c46727fd-3a51-4c4b-83f8-df9e16ec60c2)

## EFS
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/8114a43d-20f0-459c-b721-6205612c40ed)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/d7e67fe0-95e5-418d-9a9e-9eb915207669)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/cfae118a-b2a0-4e10-8580-2d390f75742c)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/26de719d-3ab4-45f5-9cf4-2cd1306de391)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/f84edfaa-2b60-477f-8920-129db7b3fc32)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/0b7f4ecd-3e43-4316-9b07-912bede0de9d)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/39370fd5-47a1-4f8d-a833-235c0ea179b1)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/1dadf73a-0447-4c91-9004-9b0a86802c5b)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/004c5fb9-68fe-422b-8286-4465996c88f5)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/e3147a86-d8d7-42a0-8262-04bc7512f1db)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/4dc0f554-0b2e-4e38-a007-547585516cd9)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/92a80432-bdfc-4d61-80a5-32cdff507536)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/5f8a54fe-295e-4dbd-863e-3ae0dea9f09f)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/b28ca760-d012-443e-b18e-b39ac432dd24)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/32dd2368-d9b2-48c6-a636-2d6472ed326f)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/bfbef5a8-1ea8-4e23-bec4-3adde76962e1)

## Install WordPress

### Code Snippets
```
1. create the html directory and mount the efs to it
sudo su
yum update -y
mkdir -p /var/www/html
sudo mount -t nfs4 -o nfsvers=4.1,rsize=1048576,wsize=1048576,hard,timeo=600,retrans=2,noresvport fs-03c9b3354880b36a6.efs.us-east-1.amazonaws.com:/ /var/www/html
```
```
2. install apache 
sudo yum install -y httpd httpd-tools mod_ssl
sudo systemctl enable httpd 
sudo systemctl start httpd
```
```
3. install php 7.4
sudo amazon-linux-extras enable php7.4
sudo yum clean metadata
sudo yum install php php-common php-pear -y
sudo yum install php-{cgi,curl,mbstring,gd,mysqlnd,gettext,json,xml,fpm,intl,zip} -y
```
```
4. install mysql5.7
sudo rpm -Uvh https://dev.mysql.com/get/mysql57-community-release-el7-11.noarch.rpm
sudo rpm --import https://repo.mysql.com/RPM-GPG-KEY-mysql-2022
sudo yum install mysql-community-server -y
sudo systemctl enable mysqld
sudo systemctl start mysqld
```
```
5. set permissions
sudo usermod -a -G apache ec2-user
sudo chown -R ec2-user:apache /var/www
sudo chmod 2775 /var/www && find /var/www -type d -exec sudo chmod 2775 {} \;
sudo find /var/www -type f -exec sudo chmod 0664 {} \;
chown apache:apache -R /var/www/html 
```
```
6. download wordpress files
wget https://wordpress.org/latest.tar.gz
tar -xzf latest.tar.gz
cp -r wordpress/* /var/www/html
```
```
7. create the wp-config.php file
cp /var/www/html/wp-config-sample.php /var/www/html/wp-config.php
```
```
8. edit the wp-config.php file
nano /var/www/html/wp-config.php
```
```
9. restart the webserver
service httpd restart
```
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/341e29af-5386-4fd7-88aa-d9c8835a8135)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/1f076032-37e4-4468-bcd0-d2eae7200657)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/08ac0126-ccea-4d49-9574-78a89f6786fb)


## ALB
### Target Group

## Route 53

## Create a Certificate Manager

## HTTPS Listener For ALB

```
/* SSL Settings */
define('FORCE_SSL_ADMIN', true);

// Get true SSL status from AWS load balancer
if(isset($_SERVER['HTTP_X_FORWARDED_PROTO']) && $_SERVER['HTTP_X_FORWARDED_PROTO'] === 'https') {
  $_SERVER['HTTPS'] = '1';
```
## Encryption
```
/* SSL Settings */
define('FORCE_SSL_ADMIN', true);
// Get true SSL status from AWS load balancer
if(isset($_SERVER['HTTP_X_FORWARDED_PROTO']) && $_SERVER['HTTP_X_FORWARDED_PROTO'] === 'https') {
  $_SERVER['HTTPS'] = '1’;
```
## WordPress Theme Selection

## Final Output 
