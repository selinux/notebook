# notebook
docker "ipython notebook"

Based on

https://registry.hub.docker.com/u/ipython/notebook/

with pdf support

## Usage ##

Run in src dir:

docker run -d -p 443:8888 \
           -v $(pwd):/notebooks/ \
           -e "PASSWORD=pass" selinux/notebook


Now you can connect to...

    [https://localhost]



