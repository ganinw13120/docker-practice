## With arguments and Environment
#### Build image with arguments
using `--build-arg`
`docker build -t env-js --build-arg NODE_VERSION=alpine3.12 .`

#### Run image with environment files
using `--env-file`
`docker run --env-file ./.env env-js`

## Plain Image
#### Build plain image
`docker build . -t env_js`

#### Run plain image
`docker run --rm env_js`