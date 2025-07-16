# GitQlient
GitQlient is the project to build and integrated a QtCreator plugin of GitQlient app

## Installing the plugin
You can find the plugin in the [release section](https://github.com/francescmm/GitQlientPlugin/releases). Once you have downloaded the plugin, copy it into the QtCreator folder where Qt is installed (Qt/Tools/QtCreator/lib/qtcreator/plugins) or in the following folders:

Linux
``~/.local/share/data/QtProject/qtcreator/plugins/<version>``

Windows
``%LOCALAPPDATA%\QtProject\qtcreator\plugins\<version>``

OSX
``~/Library/Application Support/QtProject/Qt Creator/plugins/<version>``

You need to replace <version> with the QtCreator version (e.g. 4.10.2).

The plugin should be activated by default once you have copied it, so you just will need to reboot QtCreator.

![GitQlient logo](https://github.com/francescmm/GitQlient/blob/master/src/resources/icons/GitQlientLogo96.png "GitQlient")

# GitQlient: Multi-platform Git client written with Qt

[![Master](https://github.com/francescmm/GitQlient/actions/workflows/master.yaml/badge.svg?branch=master)](https://github.com/francescmm/GitQlient/actions/workflows/master.yaml)

GitQlient, pronounced as git+client (/gɪtˈklaɪənt/) is a multi-platform Git client originally forked from QGit. Nowadays it goes beyond of just a fork and adds a lot of new functionality.

![GitQlient main screen](https://github.com/francescmm/GitQlient/blob/master/docs/assets/GitQlient.png)

## Main features

Some of the major feature you can find are:

1. Easy access to remote actions like: push, pull, submodules management and branches
2. Branches management
3. Tags and stashes management
4. Submodules handling
5. Allow to open several repositories in the same window
6. Better visualization of the commits and the work in progress
7. Better visualization of the repository view
8. GitHub/GitLab integration
9. Embedded text editor with syntax highlight for C++

For all the features take a look to the [Release Notes in the Wiki](https://github.com/francescmm/GitQlient/wiki).

## User Manual

Please, if you have any doubts about how to use it or you just want to know all you can do with GitQlient, take a look to [the user manual in here](https://francescmm.github.io/GitQlient).

It is planned to release for Linux, MacOs and Windows. However, take into account that the development environment is based on Linux and it will be the first platform released.

## Interactive UI guide (with code links)

I've set up a small (and ugly) webpage for those developers that want to get some help understanding the different parts of the UI of GitQlient and how they are connected with the C++ code.

The web shows the current UI design with links to the code of the widgets when you click on the areas of the image. The code is shown in a frame near to the image, so a 1920px screen might be needed. Since I'm not a web developer and I don't intend to dedicate too much time to that, I'll update the guide only with major releases. If anybody wants to make it pritier and knows how to do it, please contact me to see if we can collaborate.

[Check the Interactive UI guide of GitQlient.](https://francescmm.github.io/gitqlient/)
