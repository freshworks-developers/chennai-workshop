# Getting started

If you are new to Freshworks Developer ecosystem, this segment is to help you get started. There are threetwo major steps

1. Signing up a freshworks developer
2. From the developer account subscribing for a freshworks product
3. Local setup

# Signing up a freshworks developer

1. If you already have an account with us skip this step
2. By cliking the link and providing necessary details [Developer Sign up](https://developers.freshworks.com/signup/)
3. Bookmark the developer account link for future reference
4. Refer detailed instruction from [here](https://community.freshworks.dev/t/how-to-log-in-and-get-started-with-the-freshworks-developer-account/7078)


## From the developer account subscribing for a freshworks product

1. If you already have an account with us skip this step
2. When landed on App Management Portal (AMP) you will be asked to signup for at least one product to get started with
3. Select the product of your choice and signup
4. Refer to detailed instruction on [Product Sign Up](https://community.freshworks.dev/t/how-to-log-in-and-get-started-with-the-freshworks-developer-account/7078#h-1-how-to-sign-up-for-freshworks-products-from-the-developer-account-11) when in doubt


## Local setup

Kindly ensure you have gone through the [Introductory guide to freshworks app development](https://community.freshworks.dev/t/introductory-guide-to-freshworks-app-development/3589) if haven't done already

## How to get the necessary setup done?

1. Ensure you have NVM Setup locally
   1. For Mac Users use one of these steps
      1. Follow [these steps](https://github.com/nvm-sh/nvm#installation-and-update) for CLI based installation of NVM
      2. Follow steps below to Install NVM via brew
         1. Follow [Brew installation steps](https://brew.sh/) if haven't installed brew already
         2. Verify brew working  or notversion
         3. Install NVM via brew
            ```sh
            # install nvm
            brew install nvm
            # verify version
            nvm --version
   2. For Windows Users use one of the below option
      1. [Install via installers](https://github.com/coreybutler/nvm-windows/releases)
      2. Install via chocolatey
         1. [Install Chocolatey Package manager](https://chocolatey.org/install)
         2. Install NVM via chocolatey
            ```sh
            # install nvm
            choco install nvm
            # verify version
            nvm --version
            ```
    3. For ubuntu based installation
       1. Install cURL utility via command line
        ```sh
        sudo apt install curl
        ```
       2. Use cURL to install NVM via installation script
        ```sh
        curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash 
        ```
       3. The installation script creates an environment entry to the login script of the current user.
        ```sh
        source ~/.bashrc
        ```
 
2. Install Node
     ```shw
     # install node 18 via nvm
     nvm install 18
     # verify node version
     node --version
     # create alias against node
     nvm alias default 18
     ```
 3. Install build tools
     ```sh
     # for Mac first time Users
     xcode-select --install
     # verify you have xcode cli installed
     xcode-select -p
     # for windows Users install build tools for windows
     npm install --global --production windows-build-tools
     ```
 4. Install latest version of FDK
    ```sh
    # for new install
    npm install https://cdn.freshdev.io/fdk/latest.tgz -g
    # for existing Users of FDK version <9.0.0
        # remove the existing version of fdk
        npm uninstall fdk -g
        # remove the ~/.fdk folder
        rm -r ~/.fdk
        # install FDK via npm
        npm install https://cdn.freshdev.io/fdk/latest.tgz -g
    # verify the FDK version
    fdk version
    ```

Towards end of the it your output shouldbe same or higher than the listed ones

```sh
#for nvm -v
0.39.3
# for node -v
v18.15.0
# for npm -v
9.6.3
# for fdk -v
9.0.1
```

Once completed create your first freshworks application using [app development guide](app-dev-guide.md)
