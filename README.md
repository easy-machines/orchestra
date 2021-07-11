# Introduction
*Orchestra* is intended to provide an easy and lightweight interface to remote machines in order to manage remote applications' execution. In a sense it is to provide graphical and command-line interface to the remote machines for easy management. The prime reason for its existence is to handle remote Linux machines that do not have graphical environments installed for various reasons.

# User Interface
The user-interface for this project is kept in a separate repository https://github.com/easy-machines/orchestra-ui

# Linux Machine
Presently the project is targeting for controlling remote Linux machines from the ease of Graphical User Interface on Windows machines.

## Getting the Dependencies

### Debian / Ubuntu
Gather the dependencies for building *Orchestra* on Debian / Ubuntu like Linux Distributions

```
sudo apt-get install -y make gcc g++
```

### RedHat
Gather the dependencies for building *Orchestra* on Red Hat like Linux Distributions

For YUM based package management:

```
sudo yum install -y make gcc g++
```

For DNF based package management:

```
sudo dnf install -y make gcc g++
```

## Building
Download the project and go to the base directory of *Orchestra*

```
git pull https://github.com/easy-machines/orchestra
cd orchestra
```

Build the project

```
make
```
