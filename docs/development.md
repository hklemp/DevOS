# Development

## Install Tools 

Install bluebuild cli tools (https://github.com/blue-build/cli)

```` bash
podman run --pull always --rm ghcr.io/blue-build/cli:latest-installer | bash 

````

## Test Build Lokal

To test the build process use

```` bash
bluebuild validate ./recipes/recipe.yml
bluebuild build ./recipes/recipe.yml
````