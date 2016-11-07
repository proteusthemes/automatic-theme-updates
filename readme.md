# PT Automatic Theme Updates #

This is a composer package for the ProteusThemes automatic theme updates:

- ThemeForest and
- PT custom shop (probably Gumroad)

These two platforms should only offer the verification process -> one purchase code === one install.

The actual zip theme files should be pulled form our severs.

## How it works? ##

A user can add the **purchase code** to the customizer control, where he can also activate/deactivate the code (save the url of the WP installation and the purchase code to our database).

The deactivation is useful, if the user wants to migrate the site to another domain...

If the purchase code is valid, the theme updates should be available in the default WP updates section as well as in the single theme view (default WP updates functionality).