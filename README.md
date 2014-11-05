docker-captainhook
==================

Docker image that sets up [captainhook](https://github.com/bketelsen/captainhook) for getting webhook notifications.

To use this image pull it from the Docker Registry Hub:

```bash
$ docker pull ablas/docker-captainhook
```
Run the container:

```bash
$ docker run -d -p 8080:8080 -v `${HOOKS_PATH}`:/webhooks ablas/docker-captainhook
```
> You can implement your hooks in any folder at your election just note you'll need to map it to the `/webhooks`.


