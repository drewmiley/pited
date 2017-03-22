## Required Packages

*nginx
*Python3
*Git
*pip3
*virtualenv

e.g;
sudo apt-get install nginx git python3 python3-pip
sudo pip3 install virtualenv

## Nginx virtual host config

*see nginx.template.conf
*replace SITENAME with your sitename

## Running gunicorn

*see gunicorn.template.service
*replace SITENAME with yout sitename

## Folder structure

+-- home/ubuntu
	+-- sites
		+-- SITENAME
			+-- database
			+-- source
			+-- static
			+-- env
