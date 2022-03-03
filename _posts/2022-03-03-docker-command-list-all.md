---
layout: post
title:  Docker command to list all docker information
categories: [docker]
---

To list all docker container that been running on our machine, we can use the following command:

```bash
docker container ls
```

But if we want to focus only on docker name, port and image we can use specific command:

```bash
docker container ls --format "table {{.Names}}\t{{.Ports}}\t{{.Image}}"
```

So now we want to see specific and filter our docker container ( by name or by port). We can use the following command:

```bash
docker container ls -a -q --filter=name=(container name) --format "table {{.Names}}\t{{.Ports}}\t{{.Image}}"
```

---
Source:
Docker container command [link](http://manpages.ubuntu.com/manpages/bionic/man1/docker-container-ls.1.html)
