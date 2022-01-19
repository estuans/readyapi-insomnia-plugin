# Insomnia Plugin for ReadyAPI

This repository contains source code files for the Insomnia Plugin for ReadyAPI. You can use this plugin to import your Insomnia collections.

## Plugin Info

- Author: Ben Field
- Plugin version: 0.0.1
- Forked from SmartBear's Postman Collection API

## Requirements

The plugin requires ReadyAPI version 2.6 or later.

## Working With the Plugin

### Install the plugin

![Intstalling the plugin](install-plugin.png)

To install the plugin:

- In ReadyAPI, switch to the **Integrations** tab.
- Find **ReadyAPI Insomnia Plugin** and click **Install**.
- Confirm that you want to download and install the plugin.

### Import the collection

![Import insomnia collection](import-insomnia-collection.png)

To import the collection:

- Select **File > Create Project via Integration**.
- In the **Create Project via Integration** dialog, click **Insomnia collection**.
- In the **Import Insomnia Collection** dialog, click **Browse** and select the Postman collection to import.

## Build the plugin

If you want to build the plugin yourself all you need to do is clone this repository locally and run

```
mvn clean install
```

which will create the plugin jar in the target folder

## Additional Information
