# How Lepsta works
Lepsta is a very simple service to understand (on a high level).


## Architecture Summary
Lepsta provides a collaboration and automation service to developers through a cloud based platform structured in a 3-tiered architecture. Making up the tiers are two software parts that work together to make the service possible. This obviously excludes supporting services such as databases, caching applications and other general purpose parts.

### Uju (client)
Uju (means Honey is Zulu), is a version control tool designed specifically for use with the Lepsta platform.
To use Lepsta, you need to download and install Uju on your development computer. Uju runs in the background, managing data syncing, networking, versioning and more. Since Uju always knows where your repositories are sitting, it can listen to the changes you are making to provide an automation interface that can be used to improve your workflows.

### Platform (cloud)

!!! note "Note"
    Even though we refer to this platform as being on the cloud, there might be options to have it deployed in your own infrastructure. But for the purpose of creating a mental picture, we will use "the cloud" as an example here.

The online (cloud) platform is a managed application that allows developers to collaborate with one another. This is where developers can review each other's changes, manage their streams, accounts, access control and more. Repositories are created on this platform, then Uju clients are able to connect and synchronise changes over the internet.
To use Lepsta, you will need to [create an account](https://lepsta.tech/auth/signup).

### Uju (server)
Uju is also used on our servers to host and manage Lepsta repositories. The Platform provisions repositories using the server version of Uju that sits in our infrastructure. These Uju instances are really what makes it possible to create a "always-on" repository network to allow everything to happen near real-time.

## How it all comes togeter