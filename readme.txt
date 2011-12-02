WordPress Plugin's README document for developers:

Supported WordPress Versions:
================
All 3.x

What does it do:
================
Google Identity Toolkit (GITkit) helps relying party (RP) websites to support federated login easily (http://code.google.com/apis/identitytoolkit).

This is the GITkit plugin for WordPress 3.x to help website owners to integrate GITkit into their websites. It provides an Account Chooser widget, which allows users to login with their email address and password, and would like to replace that password with federated login. It currently supports Google mail, Hotmail, Yahoo! mail, AOL mail, and Google Apps mail but more identity providers will be added in the future.

Installation steps:
================
1. Turn on apache mod_rewrite module in your apache config file. Otherwise, the Google Identity Toolkit plugin will not work properly 
2. Unzip and copy the installation package "git" to the WordPress root directory "wp-content/plugins/".
3. Go to "Settings/Google Identity Toolkit", enter "APIKey" which you can get from Google Developer Console (https://code.google.com/apis/identitytoolkit/v1/devconsole.html), then click the "Save Changes" button to save your configuration.
4. Refresh your WordPress website and you will see there is a login button on the top-right of the page.



