# LocalStack Gitpod Demo

Simple demo for running LocalStack in Gitpod

Use this button to launch a Gitpod workspace with LocalStack:
[![Open in Gitpod](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/whummer/localstack-gitpod-demo)

## Demo application

To run the sample cloud application entirely within the Gitpod environment, using LocalStack, follow the steps:

1. First open the demo repo application in Gitpod Workspace 
2. On opening the demo, `gitpod.yml` configures the project by installing the tools and running the app.
3. Upon deployment, the sample app opens a network port 3000 that serves the Web application of the example.
4. Gitpod opens the demo app in the browser that sends API requests to the LocalStack edge endpoint on `4566` port, which then gets forwarded to the LocalStack instance running within the remote Gitpod environment.

You can also watch the [video](https://www.youtube.com/watch?v=CihxsFcHyEk), which thoroughly walks you through the whole process, or refer to the blog - [LocalStack x Gitpod - Run cloud applications with LocalStack and Gitpod.](https://www.gitpod.io/blog/localstack-and-gitpod)


## License

The code in this project is available under the Apache 2.0 license.
