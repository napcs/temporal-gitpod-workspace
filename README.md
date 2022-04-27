# Temporal GitPod Workspace

https://gitpod.io/#https://github.com/napcs/temporal-gitpod-workspace

Clone this repository and open it with GitPod to create a workspace where you can build Temporal applications
without setting up a local development environment.

The workspace starts a Temporal development server and a preview window showing the server. It also creates a terminal window for your worker process, your general commands, and the Temporal server.


Once the workspace is ready, you'll want the Temporal SDK for the language you're using.

If you're using Go, create a new Go application and fetch the SDK:

```
go mod init app
go get -u go.temporal.io/sdk@latest
```

If you're using TypeScript or JavaScript, create a new `package.json` file with `npm init` and add the Temporal SDK as a dependency:

```
npm init
npm i temporalio --save
```


More to come....


