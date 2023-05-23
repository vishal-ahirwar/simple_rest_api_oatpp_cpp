
### Build and Run

#### Using CMake

**Requires** 

- `oatpp` module installed. You may run `utility/install-oatpp-modules.sh` 
script to install required oatpp modules.

```
$ mkdir build && cd build
$ cmake ..
$ make 
$ ./my-project-exe  # - run application.

```

#### In Docker

```
$ docker build -t oatpp-starter .
$ docker run -p 8000:8000 -t oatpp-starter
```
