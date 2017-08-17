### Path For Upstart
	/etc/init/nginx.conf

### First reload the Upstart configuration
	initctl reload-configuration
	
### Then check the upstart job list:

	initctl list | grep nginx
### And start the job:

	initctl start nginx





