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
 - Linux, macOS or Windows 10 operating system. (**mandatory**)
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

    !!! warning "We are still working on the Windows version."
        We are still working on the Windows version and will make an announcement as soon as it is available.
        However, as a workaround, you can get it working on windows by activating the Windows Subsystem for Linux.


    
    ## Enable Windows Subsystem
    You must be on Windows 10 to activate Windows Subsystem for Linux for Uju to work.

    
    Firstly, enable Windows Subsystem for Linux (WSL) using Settings. 

    - Open Settings.
    - Click on Apps.
    - Under the "Related settings" area, click the Programs and Features option.

    ![Click the Programs and Features option](/assets/images/features.PNG)

    - Click the Turn Windows features on or off option from the left pane.

    ![Turn Windows features on or off option from the left panel](/assets/images/windowsFeatures.PNG)
    
    - Check the Windows Subsystem for Linux option.
    ![Check the Windows Subsystem for Linux option](/assets/images/windowsFeature.PNG)

    - Click the OK button.
    - Click the Restart now button.
    Once you complete the steps, the environment will be configured to download and run the distros of Linux on Windows 10.

    Head on to <a href="https://docs.microsoft.com/en-us/windows/wsl/install-win10https://docs.microsoft.com/en-us/windows/wsl/install-win10" target="_blank"> Microsoft Docs </a> to complete the remaining steps or to <a href="https://www.windowscentral.com/install-windows-subsystem-linux-windows-10" target="_blank"> Windows central </a> for more detailed instructions. 

    !!! Note "Note"
        If you are running Windows 10 version 1903 or 1909, open "Settings" from your Windows menu, navigate to "Update & Security" and select "Check for Updates". Your Build number must be 18362.1049+ or 18363.1049+, with the minor build # over .1049. Read more: WSL 2 Support is coming to Windows 10 Versions 1903 and 1909.
        
        See the troubleshooting instructions on  <a href="https://docs.microsoft.com/en-us/windows/wsl/install-win10https://docs.microsoft.com/en-us/windows/wsl/install-win10" target="_blank"> Microsoft Docs. </a>
    
    

    Once you have installed the Linux distro eg. Ubuntu or Mint, launch it.
    
    ![Launch the Linux distros](/assets/images/launch.png)

    - Create a username for the Linux and press Enter.
    - Specify a password and press Enter.


    ![Create a username and password](/assets/images/linux.PNG)


    ## Setup Uju in your Linux distro

    You can install Uju by running one of these commands on your terminal.
        ```
        curl https://lepsta.tech/get | sh
        ```
        or
        ```
        wget -qO- https://lepsta.tech/get | sh
        ```

    ![Get Uju](/assets/images/downloadUju.PNG)



## Login from Uju
For you to start working on your Lepsta repositories Uju needs to have access to your Lepsta Platform account. To authorize Uju, you need to login from the commandline interface. Simply run the following command, and you are good to go:

```
uju login -u <username>
```

!!! attention "Attention: Did any of these steps fail?"
    Just in case some of these steps did not go according to documentation, consider making a search on the top bar to check if the issue and solution are documented. 