# Parallel Computing with Python

Notebooks for [Master for BigData]()

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/mesfind/bigdata/master)
[![JupyterBook](https://github.com/mesfind/bigdata//workflows/book/badge.svg)](https://github.com/mesfind/bigdata/actions/)

- [Website](https://mesfind.github.io/bigdata) generated with [jupyterbook](https://jupyterbook.org).
- [Website](https://mesfind.github.io/bigdata/quarto/intro.html) generated with [quarto](https://quarto.org).

The content of these notebooks are made thanks to these [references](https://mesfind.github.io/bigdata/intro.html).

## Run Jupyter notebooks with docker

### Get docker app

 - [Mac](https://www.docker.com/docker-mac)
 - [Windows](https://www.docker.com/docker-windows)
 - [Linux](https://runnable.com/docker/install-docker-on-linux)

You can run these notebooks with Docker. The following command starts a container with the Notebook 
server listening for HTTP connections on port 8888 and 4040 without authentication configured.

```
git clone https://github.com/mesfind/bigdata.git
docker run --rm -v $PWD/bigdata:/home/admin/ -p 8888:8888 -p 4040:4040 mesfind/bigdata
```

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
