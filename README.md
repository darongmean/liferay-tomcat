#Liferay in docker

* Liferay version: liferay-portal-tomcat-6.2-ce-ga2-20140319114139101
* Base image on busybox to get smaller image (~600M)
* Move tomcat logs file to $LIFERAY_HOME/logs/tomcat

Expose port 8080

#Volumes

* /var/liferay: Liferay home folder

#Reference

* https://registry.hub.docker.com/u/jeanblanchard/busybox-java/
* https://registry.hub.docker.com/u/snasello/liferay-6.2/
