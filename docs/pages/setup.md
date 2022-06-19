## Lepsta Account
To get started you need to register a Lepsta account using your email and password combination. You can click [here](https://lepsta.tech/auth/signup) to create a new account, if you have not done so already. You will be asked to verify your email address after signing up. Please check your email, and check your spam box if it doesnt appear on your primary inbox.

## Install Uju

### System requirements

Uju is a version control system that you have to install in your system. You need the following in order to use it:

> * A computer that runs Linux or 
* Mac Operating Systems . 

WindowsOS version is in development. However, Windows users who want to use Lepsta are encouraged to partition their machines and install a Linux distro in order to use Uju.


### Uju Setup
Once you have setup your account and logged in on the platform,the next thing to do is to create a new repository by clicking the ``repositories`` tab and follow these steps:

1. Create a new repository. You can choose to create a new empty repository or import and existing one from Github ot Bitbucket

![Create repo ](/assets/images/create_repo.gif "create repo")

2. Add a new device. Lepsta allows you to install Uju on multiple devices so that you can simply backup your work to multiple devices including servers. 


![login locally](/assets/images/login-to-uju.gif "Login locally")

To add a new device to your current machine copy the commands below, paste and run it on your terminal

### Linux or MacOs Uju installation commands

Depending on your operating system, you might have `curl` or `wget` preinstalled.
You can install Uju by running one of these commands on your terminal.


``curl https://lepsta.tech/get | sh``

or

``wget -qO- https://lepsta.tech/get | sh``


### Login to authorise uju access to online repo
To start making changes to your repositories you are required to link your online Lepsta account to Uju so that Uju can replicate your changes online. To authorize Uju, you need to login from the commandline interface. 

By default Uju will ask you to enter your username and password after installation. You can enter the username and password combination created on the platform, or you can simply run the following command, and you are good to go:


``uju login -u <username>``


![Login from Uju on your command line!](/assets/images/login-to-uju.gif "Login from Uju")\

# You are ready to go!

Now that Uju is setup and ready. The next thing to do is to create a Stream to work on. You can check the Guides on how to do that. 