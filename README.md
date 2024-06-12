# rancher-extensions

## Pre-requisites
* node -> 16.x
* yarn -> 1.22.x

## Creating Rancher Extensions

```shell
# Create the rancher app
yarn create @rancher/app -t -w

# install the packages
yarn install

# Creating a new extension
yarn create @rancher/pkg test 
```

## Building and Loading extensions

```shell
 # Note the version number provided is bound to package.json
 # Use the -f flag to build an already built extension, typically used to override versions
 yarn build-pkg test

# Server the packages
yarn serve-pkgs
```
