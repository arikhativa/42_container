# pool-tester-container
This project helps you run a docker container with the dependencies of the 42 madrid pool-tester

The container will have valgrind inside, so you can use just that if you want

## How to use
```bash
git clone <repo>
cd <repo>
make run
make enter
```

after these cmds you will be inside the container.
your fs (file system) should me iside the container as well
you can run valgrind <your-exec> and see what happens.

good luck!
