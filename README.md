# build_env_c
Dockerized Environment for build C projects


### Usage

__Compilation__

Just run `docker run --rm -v "$PWD:/src" -it yuanw/sdk-env`

Or add as an alias:

`alias mksdk='docker run --rm -v "$PWD:/src" -it yuanw/sdk-env'`

And run `mksdk`