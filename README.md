This is the result of [Creating a Cloud Native Buildpack](https://buildpacks.io/docs/create-buildpack/).

# How to use

## Prerequisites

* Install pack CLI accoding to [Installing pack](https://buildpacks.io/docs/using-pack/install-pack/)

* Install Docker

## Run

```bash
git clone https://github.com/hidekazuna/Ruby-Cloud-Native-Buildpack.git
pack build test-ruby-app --buildpack Ruby-Cloud-Native-Buildpack/ruby-cnb  --path Ruby-Cloud-Native-Buildpack/ruby-sample-app/
docker run -p 8080:8080 test-ruby-app
```

# License

Apache License, Version 2.0

