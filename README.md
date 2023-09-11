# empty

## Install

##### HTTPS
```shell
git clone https://github.com/yarscript/monorep-root-bp.git --recurse-submodules
```
### OR
#####  SSH
```shell
$ git clone git@github.com:yarscript/monorep-root-bp.git
```

-----------
##### Submodules update init
```shell
$ git submodule update --init --recursive
```
##### Pull submodules
```shell
$ git pull --recurse-submodules
```

--------

### Bootstrap
```shell
#
$ docker-compose up

### Expected result

# [+] Running 4/4
# ✔ Network monorep-root-bp_default       Created                                                                                                                                                0.6s 
# ✔ Container monorep-root-bp-rabbitmq-1  Created                                                                                                                                                1.9s 
# ✔ Container monorep-root-bp-service2-1  Created                                                                                                                                                0.5s 
# ✔ Container monorep-root-bp-service1-1  Created                                                                                                                                                0.4s 
# Attaching to monorep-root-bp-rabbitmq-1, monorep-root-bp-service1-1, monorep-root-bp-service2-1

$ docker ls
```


## Submodule add
```sh
$ # submodule add:
$ git submodule add https://github.com/yarscript/child-first-ms-bp.git child-first-ms-bp
```

```sh

$ git submodule add git@github.com:yarscript/child-second-ms-bp.git

### add force

$ git submodule add --force https://github.com/yarscript/child-first-ms-bp.git child-first-ms-bp

### fetch



###

$ rm -rf child-first-ms-bp
$ git rm -rf child-first-ms-bp 
```

