# How to Install and Use Docker for Software Development

Docker is an open platform for developing, shipping, and running applications.
If you are familiar with the concept of Virtual Machine and VirtualBox, but you
are unfamiliar with the concept of Docker container and Docker image, just know
that Docker serves a similar to a Virtual Machine but uses a different
technology, which uses less resources on your computer. A Docker image is
analogous to a Virtual Machine image, and a Docker container is analogous to a
Virtual Machine. If you still don't understand what I am talking about, it is
ok. Just follow the guide, because the concept is not important.

# Install Docker and Load Our fuckseashell Image

Steps:

1. Install Docker. Follow the offical guide here:
   https://docs.docker.com/get-docker/ to download and install Docker Desktop
   for your system.

2. After Docker Desktop is installed, download our [fuckseashell template
   directory](https://github.com/ylilarry/fuckseashell-template/archive/main.zip),
   extract the zip file to somewhere you want to store your code to.

3. Next, open terminal and `cd` to the `fuckseashell-template` directory above, then run following command:
```
docker compose up -d
```

Now you have your fuckseashell SDK for CS136 running successfully.

The next step is to learn [how to use Visual Studio Code (VSC) to develop C code](how-to-vsc.md).

***Attention: if you are following this guide, ie, using our fuckseashell image
instead of developing locally on your computer, then after opening VSC you need
to attach VSC to the fuckseashell container.***

