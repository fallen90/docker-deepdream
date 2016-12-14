# docker-deepdream
> Headache relieving docker image to start you up with Google's Deep Dream project.

To start open up your terminal and type in :
```bash
docker run -d -p 443:8888 -e "PASSWORD=password" -v /path/to/your/files:/src fallen90/docker-deepdream
```
> You can also map port 8888 (iPython web interface) to a different port (80)

After that, goto `https://<docker-api>/`

## Features / Installed
	- iPython 3.x (base image)
	- Anaconda (2.0.1)
	- caffe (cpu based, local)