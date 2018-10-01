# Magento 2 Community Edition example for Platform.sh

This project provides a starter kit for Magento 2 Community Edition (M2CE) projects hosted on Platform.sh. It is strongly recommended that M2CE projects on Platform.sh start from this repository as Magento does require some modification to run correctly.

## Starting a new project

To start a new project based on this template, follow these 3 simple steps:

1. Clone this repository locally.  You may optionally remove the `origin` remote or remove the `.git` directory and re-init the project if you want a clean history.
 
2. Create a new project through the Platform.sh user interface and select "Import an existing project" when prompted.

3. Run the provided Git commands to add a Platform.sh remote and push the code to the Platform.sh repository.

That's it!  Your Magento site will deploy and you'll be able to view it in a browser.  Note that as part of the setup process the admin account is already created for you.  The initial username `admin` has a password of `admin123`.  You will be required to change it the first time you login.

## Using as a reference

You can use this repository as a reference for your own projects, and borrow whatever code is needed.  The most important parts are the [`.platform.app.yaml`](/.platform.app.yaml) file and the [`.platform`](/.platform) directory.
