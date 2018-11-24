# MyMenu

This application contains a list of restaurants and their menus.
You can add, delete and edit restaurants and menus.

## Usage

### Setting up the environment

The usage of this report is intended to be done by using Vagrant and VirtualBox. Therefore, both of them need to be installed.

Once you have both of them installed in your computer. Download the VM configuration by fooking and then cloning this [repo](https://github.com/udacity/fullstack-nanodegree-vm).

Then, `cd` into the **vagrant** directory and paste the items inside the folder `my-menu` here. After this, run `vagrant up` to download the Linux OS and install it.

After this, you just need to do `vagrant ssh` to log in into the VM.

### Running the report

In order to see the report, run the following commands:
* Run `python database_setup.py` in order to create the database
* Run `python lotsofmenus.py` to populate the database
* Run `python finalproject.py` and navigate to localhost:5000 in your browser

## Credits

### Images

* [Restaurant](https://pixabay.com/en/breakfast-food-eating-meal-morning-690128/)

### Contributors

* Sara Garci <rsaragarci@gmail.com>

## License

© Copyright 2018 by Sara Garci. All rights reserved.
