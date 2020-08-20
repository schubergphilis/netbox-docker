# Netbox

The Netbox images used for IPAM. The IPAM setup consists of 2 images:

* [Netbox](https://github.com/netbox-community/netbox): The Netbox application
* [NGINX](https://github.com/nginxinc/docker-nginx): Required for serving the static files

Both images are build and deployed at the same time with the version of Netbox.

Current versions

* Netbox: `v2.8.9`
* NGINX: `1.17.9`
