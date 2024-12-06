# Eidolon Browser Agent

This project serves as an example browser agent.

This agent can manipulate a browser when directed by another user / agent.

This respository is a WIP. Prompt engineering is evolving and kubernetes is not yet preconfigured (browser-service needs to be launched manually).

## Running the Server in Docker

First you need to clone the project and navigate to the project directory:

```bash
git clone https://github.com/eidolon-ai/browser-agent.git
cd agent-machine
```

Then run the server using docker, use the following command:

```bash
make docker-serve
```

The first time you run this command, you may be prompted to enter credentials that the machine needs
to run (ie, ANTHROPIC API Key).

If the server starts successfully, you should see the following output:

```
Starting Server...
INFO:     Started server process [34623]
INFO:     Waiting for application startup.
INFO - Building machine 'local_dev'
...
INFO - Server Started in 1.50s
```
