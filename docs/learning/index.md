# Learning Rundeck

With Rundeck, it is simple and easy to create automation workflows from existing tools or scripts. The Learning section includes a Getting Started Tutorial and How to Guides that  help new users quickly become productive with the Rundeck server and tools. Instructions are provided for both Enterprise and Community versions of Rundeck.

Visit the [Tutorials](/learning/tutorial/preparing) to see practical step-by-step guides that help you get your Rundeck account up and running - starting with installing and configuring Rundeck. Use the [How To](/learning/howto/overview) section accomplish the task using the Rundeck Enterprise version and where applicable, the steps for the Community version.

The *How To* articles go deeper into specific topics and are also commonly built around the Welcome Project plus completion of the base tutorial.

## Getting Started

### Essential Concepts

Several fundamental concepts underlie and drive the Rundeck system. If you are a new user, knowing about them will help you use or integrate Rundeck into your environment.

The first step is to learn some key Rundeck Terms in our [Terminology Tutorial](terminology.md).

### Using Rundeck

If a running Rundeck instance isn't already available to you,
there are a couple ways you can try it.

#### Welcome Projects

Both Rundeck product versions, Enterprise or Community, have a companion set of code at the following links. These code bases allow running Rundeck in a Docker environment with the Welcome Project preloaded.

- Enterprise: [https://github.com/rundeckpro/welcome-project](https://github.com/rundeckpro/welcome-project)
- Community: [https://github.com/rundeck/welcome-project-community](https://github.com/rundeck/welcome-project-community)

Follow the readme steps for more information about getting the environments started.

:::tip
Note: The Enterprise version will require a license file. If you aren’t currently an Enterprise customer and you’re interested in using that please [contact us here](https://www.rundeck.com/see-demo).
:::

:::warning
It is possible to run the Welcome Projects in other environments, but some exercise steps will need to be adjusted for your specific environment
:::

#### Download and Install
Get the latest release at our [download](https://download.rundeck.com/) site and
  install the Rundeck software. There are several package formats.
  Choose the one that best suits the target infrastructure.

  After installation, be sure Rundeck has been started.
  ::: tip
  See [Startup](/administration/maintenance/startup.md) to learn how to  startup and shutdown rundeck.
  :::

The default port for the web interface is `4440`. If you
installed Rundeck on your local machine, go to this URL: `http://locahost:4440`

### Login

Rundeck requires every user to login. The default installation
defines an "admin" user with access to perform all actions.
Use "admin" for username and password.

![Login form](~@assets/img/fig0202.png)