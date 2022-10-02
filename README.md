# Sadpod broken webserver

Inspired by the excellent [Sad Servers](https://sadservers.com), this is an implementation of the "Tokyo" scenario, where a webserver is serving `index.html` from `127.0.0.1:80`, but it's not available.

## Running in Gitpod

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/lpmi-13/sadpods-webserver)

This is a great use case for running an exercise in Gitpod, since the custom Docker image is very large, and it's much easier to pull it to a remote pod. There's also some Gitpod magic going on behind the scenes which means that pull and running the image locally won't work anyway.

## The task

There's a webserver trying to serve content at `127.0.0.1:80`, but it's not currently working. See if you can fix it!

## Checking your solution

When you can successfully run

```
curl 127.0.0.1:80
```

and see

```
hello sadpod
```

then you've fixed it!
