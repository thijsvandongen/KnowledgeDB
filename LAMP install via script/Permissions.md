# Permission setting www folder

Permission to make the user write write on www-folder

```shell
sudo adduser <username> apache

sudo chown -R apache:apache /data/www
sudo chmod -R g+w /data/www
````

After this you can edit all teh files and make new folders
