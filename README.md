# This repo define some security features for wordpress


## Creating `.env` file

The creation of the `.env` file allows you to avoid coding the
critical credentials on the `wp-config.php` file.

### Follow the steps below to do so

The process is to copy this repository to your project directory at the root folder.
Replace the `wp-config.php` file with the provided in this repository. Create the `.env` file and
set the correct credentials ( we provide an example of `.env` file `.env.example`).

### To do

This section describes improvements that we make on this repository

- [ ] add `Authentication Unique Keys and Salts` to the `.env` file in propose to remove them
from the `wp-config.php

