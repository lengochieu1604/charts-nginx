# Helm Charts nginx

Usage
Some common Helm commands for you

## Add repo before using
    $ helm repo add lengochieu1604 https://raw.githubusercontent.com/lengochieu1604/charts-nginx/main/
    "lengochieu1604" has been added to your repositories

## Search for charts, or list all the charts by repo's name
    $ helm search repo lengochieu1604
![image](https://user-images.githubusercontent.com/98753976/162600867-1a5fd7de-d540-4374-a786-f4031e1defbe.png)

## Get configurations (values file)
    $ helm show values lengochieu1604/nginx2 > myvalues.yaml

## Install chart with your configurations
    $ helm install nginx3 lengochieu1604/nginx2
![image](https://user-images.githubusercontent.com/98753976/162600921-8353acf5-348d-4c35-ac10-d6a31a92b6a1.png)

## Output
![image](https://user-images.githubusercontent.com/98753976/162600987-26334f05-cf00-4d78-a5e6-d98c5f173618.png)

