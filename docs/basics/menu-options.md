# Menu Options

Upon running DSAC, you will be presented with a few options

![Main Menu](https://i.imgur.com/8u5hiyF.png)

## Quick Setup

The "Quick Setup Configurations" menu option will allow you to select app types to have DSAC create and configure together. DSAC will then run DockSTARTer to install Docker, Docker Compose, and docker configurations for these apps.

By default, all the app types are selected. Running it like this will give you a media setup with apps that are connected together. All you will have to do is configure the applications to your liking.

![Quick Setup Menu](https://i.imgur.com/l2gqFpp.png)

## Custom Setup

The "Custom Setup" menu option will allow you to select apps you want to run. DSAC will then run DockSTARTer to install Docker, Docker Compose, and docker configurations for these apps.

Any apps that DSAC supports will have "(DSAC Supported)" at the beginning of its description. If you select two that can be linked together, DSAC will handle adding those links to the applications.

In addition, if you ever want to remove an application, you can use this option to deselect an app, and it will be removed for you.

![Imgur](https://i.imgur.com/pnJeuFa.png)

## Configure Existing Containers

The "Custom Setup" menu option will use Docker commands to find supported apps and link any together that can be.

This DOES NOT use DockSTARTer.