# Temporal GitPod Workspace

Clone this repository and open it with GitPod to create a workspace where you can build Temporal applications
without setting up a local development environment.

The workspace starts a Temporal development server and a preview window showing the server.

You'll want the Temporal SDK for the language you're using. 

If you're using Go:

```
go mod init app
go get -u go.temporal.io/sdk@latest
```

If you're using TypeScript or JavaScript:

```
npm init
npm i temporalio --save
```


