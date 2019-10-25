# Upstream System Config 🚀

![Proudly written in Bash](https://img.shields.io/badge/written%20in-bash-ff69b4.svg) ![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)

This is a collection of idempotent scripts I use to configure my system for work.

**Requirements:** Ubuntu 18.04+

## Key Features

The following programs / libraries will be installed on your system:
* **[SDKMAN](https://sdkman.io/)** - This a tool for managing parallel versions of multiple **Software Development Kits**
  - Used to install Java 8, 11 and Maven 3
  - Used to switch between JDK 8/JDK 11
* **[Jetbrains Toolbox](https://www.jetbrains.com/toolbox-app/)** - Helps you to manage your JetBrains tools (*e.g. Intellij-IDEA*)
  - Install
  - Update automatically
  - Update the plugins together with IDE
  - Roll back and downgrade
* **Apache Tomcat**
* **[Apache JMeter](https://jmeter.apache.org/)** - A load testing tool
* **[Wiremock](http://wiremock.org/)** - WireMock is a flexible API mocking tool for fast, robust and comprehensive testing
* **Docker**
* **Kubectl**
* **Helm**
* **[Kubectx](https://github.com/ahmetb/kubectx)** - Switch faster between clusters and namespaces in kubectl
* **Slack**
* **[Brave Browser](https://brave.com/)**

Also, there are some custom modifications for Gnome, which can be found at

```
config/gnome3.bsh
```

## How To Use

To clone and run this set of scripts, you'll need [Git](https://git-scm.com) installed on your computer. From your command line:

```bash
# Clone this repository and include all the submodules
$ git clone --recurse-submodules -j8 git@github.com:mackatozis/work-system-config.git

# Go into the repository
$ cd upstream-system-config

# Install the scripts
$ ./install.bsh

# Open Jetbrains Toolbox to install Intellij-IDEA
$ jetbrains-toolbox
```
## Contributing

Who doesn't love contributions! Check out the [Contribution guide](CONTRIBUTING.md) for more information.
