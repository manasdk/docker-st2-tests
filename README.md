# docker-st2-tests
Docker files to run StackStorm tests

Required images to run tests -

```
mongo                 2.4                 775aa603e1f9        2 weeks ago         344.4 MB
ubuntu                14.04               1d073211c498        2 weeks ago         187.9 MB
rabbitmq              3.5.0               a030f560d2c3        7 months ago        143.4 MB
```

Commands -
various forms of `docker run` with `--links`. 

Also, changes https://github.com/StackStorm/st2/tree/docker_compat are required. Likely, https://github.com/dennybaa/st2-packages
can help make a lot mroe progress.
