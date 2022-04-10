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
    $ helm show values lengochieu1604/ambassador-ssl > myvalues.yaml

## Install chart with your configurations
    $ helm install mywebsite-ssl lengochieu1604/ambassador-ssl
  
## List of charts
    Ambassador-SSL : install Let's Encrypt certificate for your Ambassador API Gateway (Ambassaador Edge Stack)
    (updating new chart here...)
