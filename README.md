# Electron Projects

## Build over 9 cross-platform desktop applications from scratch

### Installation

#### Install Visual Studio Code

Setting up Visual Studio Code is very simple and, thanks to Electron's support, the process doesn't differ much across platform. Let's get started:

1. Navigate to https://code.visualstudio.com/. An installation package will be suggested to you regarding you current operating system. It is also possible to choose from a list of available distributions.

2. Click the big Download button to get a .dmg installer form macOS, an .msi file for Windows, or a .deb package for Debian-based Linux distributions.
3. Run the corresponding file and follow the on screen instructions. You don't need to customize anything during the setup process.

### Install on Windows System

#### Install Node.js on Windows

1. Navigate to https://nodejs.org/en and get the corresponding installer. Note that the website detects your platform for you and suggests the corresponding installer package. For Windows, you are going to see the Download for Windows (x64) label and two buttons where you can select either the LTS, that is, the stable LTS version, or a current one, with the most recent cutting-edge features.

2. Download and run the installation file. Proceed with the setup wizard and use the default settings—these are usually pretty reasonable.

### Install on Linux System

#### Installing Visual Studio Code for Ubuntu

If you are using Ubuntu Linux as your primary development machine, you can download Visual Studio Code from the Ubuntu Software Center. Just type code or visual studio code into the search box - you should get the link to the corresponding package.

#### Install Node.js on Linux

Ubuntu usually doesn't ship with the Node.js and NPM tools out of the box. You need to install them
separately.

To install Node.js, follow these steps:

1. Run the following command:

sudo apt install -y nodejs

2.- Now, we need to verify that Node.js has been installed. You can check the version that you've installed in the Terminal application by using the following command:

node --version

The system's output, which will be the version's value, will be for instance v8.11.4 or higher.

To install NPM, follow these steps:

1. Use the following command:

sudo apt install -y npm

2. The fastest way to check that NPM has been installed is to check its version. You can do so by using the following command:

npm --version

The version number should be 5.8.0 or higher.

### Install on Mac OS

#### Installing Git

Git comes preinstalled with all macOS versions. To verify this, launch the terminal application and run the following command:

git --version

The output should be similar to the following:

git version 2.17.2 (Apple Git-113)

Please note that it isn't critical if your system's version of Git doesn't match the one in this example.

#### Install Node.js

You can find the necessary installation packages by navigating to https://nodejs.org

Note  that Node.js typically comes in two flavors: the Long-Term Support(LTS) version, which is suitable for most users, and the Current version, which provides the most cutting-edge features and enhancements.

1. First we need to download and install Node.js The website automatically detects your browser and platform and suggest the appropiate packages for you to download. For macOS, you are going to see the Download for macOS (x64) label and two big download buttons.

2. Choose any version and click the corresponding button to get the relevant installer package. The installation process for the macOS platform is pretty straighforward. Keep all the default settings; proceed with the wizard's step until the setup is over.

3. In the terminal application, run the following commands to verify that you have Node.js and NPM installed on your machine:

node -v
npm -v

4. The system's output should be similar to the following, though their version may vary:

v12.13.0
6.12.1

 

