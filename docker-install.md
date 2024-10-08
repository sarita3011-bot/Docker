https://docs.docker.com/engine/install/ubuntu/

Tip: preview script steps before running

You can run the script with the --dry-run option to learn what steps the script will run when invoked:

```
 curl -fsSL https://get.docker.com -o get-docker.sh
 sudo sh ./get-docker.sh --dry-run
```

This example downloads the script from https://get.docker.com/ and runs it to install the latest stable release of Docker on Linux:

```
 curl -fsSL https://get.docker.com -o get-docker.sh
 sudo sh get-docker.sh
Executing docker install script, commit: 7cae5f8b0decc17d6571f9f52eb840fbc13b2737
<...>
```

https://github.com/docker/docker-install

From https://get.docker.com:

```
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh
```

From https://test.docker.com:

```
curl -fsSL https://test.docker.com -o test-docker.sh
sh test-docker.sh
```

From the source repo (This will install latest from the stable channel):

```
sh install.sh
```
