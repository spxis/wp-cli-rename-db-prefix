WP-CLI Rename Table Prefix
===============================

A [WP-CLI](http://wp-cli.org/) command to rename WordPress' table prefix. This is based on Ian Dunn's wp-cli-rename-db-prefix and was create to prevent less confusion when trying to modify the default "$table_prefix" value in the sample wp-config.php file of a new wordpress installation.

## Installing

`wp package install spxis/wp-cli-rename-table-prefix`

## Usage

`wp rename-table-prefix <new_prefix>`

You will be prompted for confirmation before the command makes any changes.

## Warning

Use this at your own risk. If something goes wrong, it could break your site. Before running this, make sure to back up your `wp-config.php` file and run `wp db export`.

## Notes

A lot of the code is based on [iThemes Security](https://wordpress.org/plugins/better-wp-security/).
