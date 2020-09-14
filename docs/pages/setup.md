# Setup 

To start using Lepsta, you need two things.

 - An account on the [Lepsta Platform](https://lepsta.tech/auth/signup).
 - A Linux, macOS or Windows computer running Uju (our version control tool).

This guide will help you set up both of these things.


## Create a Lepsta Platform account
To create a new account, <a href="https://lepsta.tech/auth/signup" target="_blank">click here</a>. All you will need is your own email address, and a strong password.
Alternatively, Lepsta lets you setup your account using third party authentication providers like Google, GitHub and Bitbucket.

!!! note "Note"
    Authorising your development computers to access your Lepsta Platform account still requires that you set up a password. So, even if you sign up with an OAuth service provider, you will be asked to set up a password, even though this might change in the future.


## Install Uju
Uju is a version control server designed specifically to work with the Lepsta Platform. You need to have it installed to contribute to your repositories.

### System Requirements
 - Linux, macOS or Windows operating system. (**mandatory**)
 - <a href="https://facebook.github.io/watchman/docs/install.html" target="_blank">Watchman</a> (**recommended**)

### Installation instructions

=== "Linux"
    Depending on your operating system, you might have `curl` or `wget` preinstalled.
    You can install Uju by running one of these commands on your terminal.
    ```
    curl https://lepsta.tech/get | sh
    ```
    or
    ```
    wget -qO- https://lepsta.tech/get | sh
    ```

=== "macOS"
    Depending on your operating system, you might have `curl` or `wget` preinstalled.
    You can install Uju by running one of these commands on your terminal.
    ```
    curl https://lepsta.tech/get | sh
    ```
    or
    ```
    wget -qO- https://lepsta.tech/get | sh
    ```

=== "Windows"

    !!! warning "Windows version  is not available yet"
        We are still working on the Windows version and will make an announcement as soon as it is available.

## Login from Uju
For you to start working on your Lepsta repositories Uju needs to have access to your Lepsta Platform account. To authorize Uju, you need to login from the commandline interface. Simply run the following command, and you are good to go:

```
uju login -u <username>
```

!!! attention "Attention: Did any of these steps fail?"
    Just in case some of these steps did not go according to documentation, consider making a search on the top bar to check if the issue and solution are documented. 