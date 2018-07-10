# WP Rocket for Conditional Gravity Forms
## Exclude Files from Defer JS

This script with exclude specific files from defer JS option.

This has been adjusted to solve the issues found with conditional logic in Gravity Forms where a form is totally hidden from view.

By adding jquery, gravity forms and conditional logic files to this filter we are able to ensure gravity forms work with WP Rocket defer loading method.

For the original article in WP Rocket on the Defer files see the WP Rocket Documentation:
* [Exclude files from defer JS](http://docs.wp-rocket.me/article/976-exclude-files-from-defer-js)

For information on what this code does check the blog here:
* https://www.diviframework.com/

To be used with:
* any setup where “Load JS files deferred” is enabled

Last tested with:
* WP Rocket 2.10.x
* WordPress 4.7.x
