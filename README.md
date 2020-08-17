# dapr-grpc-event-subscriber-template

[![Test](https://github.com/mchmarny/dapr-grpc-event-subscriber-template/workflows/Test/badge.svg)](https://github.com/mchmarny/dapr-grpc-event-subscriber-template/actions?query=workflow%3ATest) ![Release](https://github.com/mchmarny/dapr-grpc-event-subscriber-template/workflows/Release/badge.svg?query=workflow%3ARelease) ![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/mchmarny/dapr-grpc-event-subscriber-template) [![Go Report Card](https://goreportcard.com/badge/github.com/mchmarny/dapr-grpc-event-subscriber-template)](https://goreportcard.com/report/github.com/mchmarny/dapr-grpc-event-subscriber-template)

## template usage 

* Click "Use this template" above and follow the wizard to select owner and name your new repo
* Clone your new repo and navigate to it (e.g. `git clone git@github.com:<USERNAME>/<REPO-NAME>.git && cd <REPO-NAME>`)
* Initialize your project to set the package names and update imports (`make init`)
* Write your subscription event handling logic 

### common operations

Common operations to help you bootstrap a Dapr gRPC services development in `go`:

```shell
$ make help
tidy                           Updates the go modules and vendors all dependencies
test                           Tests the entire project
build                          Builds local release binary
run                            Builds binary and runs it in Dapr
event                          Publishes sample message to Dapr pubsub API
image                          Builds and publish docker image (requires `DOCKER_USER` variable)
lint                           Lints the entire project
tag                            Creates release tag
clean                          Cleans up generated files
reset                          Resets go modules
help                           Display available commands
```

This project also includes GitHub actions in [.github/workflows](.github/workflows) that test on each `push` and build images and mark release on each `tag`. Other Dapr GitHub templates to accelerate development:
	
* [dapr-grpc-event-subscriber-template](https://github.com/mchmarny/dapr-grpc-event-subscriber-template)
* [dapr-http-event-subscriber-template](https://github.com/mchmarny/dapr-event-subscriber-template)
* [dapr-ui-app-template](https://github.com/mchmarny/dapr-ui-app-template)
* [dapr-http-cron-handler-template](https://github.com/mchmarny/dapr-http-cron-handler-template)

## Disclaimer

This is my personal project and it does not represent my employer. I take no responsibility for issues caused by this code. I do my best to ensure that everything works, but if something goes wrong, my apologies is all you will get.

## License

This software is released under the [MIT](./LICENSE)
