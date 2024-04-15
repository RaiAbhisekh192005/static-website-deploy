# static-website-deploy

```
sudo su -
yum update -y
yum install -y httpd
systemctl status httpd
systemctl enable httpd
systemctl start httpd
mkdir temp
cd temp
```
```
wget "object URL of S3"
ls
unzip "filename.zip (filename of your zip file)"
cd "folder name"
mv * /var/www/html
```
