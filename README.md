# OpenUI5 OData V4 Tutorial

This app represents my own implementation of the openUI5 OData V4 tutorial at

https://sdk.openui5.org/ --> Get Started: Setup, Tutorials and Demo Apps --> OData V4 (https://sdk.openui5.org/topic/15d84f36c0594cb2b3295aa1f55cb961)

## Requirements

Either [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) for dependency management.

## Preparation

Use `npm` (or `yarn`) to install the dependencies:

```sh
npm i
```

## Run the App

Execute the following command to run the app locally for development in watch mode (the browser reloads the app automatically when there are changes in the source code):

```sh
ui5 serve -o index.html
```

or 
```sh
ui5.cmd serve -o index.html
```

As shown in the terminal after executing this command, the app is then running on http://localhost:8080/index.html. A browser window with this URL should automatically open.

(When using yarn, do `yarn start` instead.)

## Run app without Mock Server

In the `index.html` file, remove the line `data-sap-ui-oninit="module:sap/ui/core/tutorial/odatav4/initMockServer"`.

This will lead to cross-origin resource sharing (CORS) problems. 

For more information, see Request Fails Due to Same-Origin Policy (Cross-Origin Resource Sharing - CORS):
https://sdk.openui5.org/topic/5bb388fc289d44dca886c8fa25da466e.html

## License

This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.

## Implemented Parts of the Tutorial

* [Done] Step 1: The Initial App
* [Done] Step 2: Data Access and Client-Server Communication
* [Done] Step 3: Automatic Data Type Detection
* [Done] Step 4: Filtering, Sorting, and Counting
* [Done] Step 5: Batch Groups
* Step 6: Create and Edit
* Step 7: Delete
* Step 8: OData Operations
* Step 9: List-Detail Scenario
* Step 10: Enable Data Reuse
* Step 11: Add Table with :n Navigation to Detail Area
