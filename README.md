# checklist
A WPTRT project with a basic checklist for authors and reviewers

This checklist needs to be completed before the review can start.

How to use the checklist:

Check each item on the list.

Mark the item with a X once complete.

Example: [ X ] A copyright statement for the theme is included in: readme.txt.



== Checklist
* License & Copyright

[  ] A copyright statement for the theme is included in: (file name)

[  ] License and copyright information for all images, icons, fonts, scripts and styles is included in: (file name)

* Scripts and styles

[  ] All minified files are accompanied by non minified files.

[  ] All scripts and styles are enqueued.

[  ] If jQuery, images loaded or Masonry is used, the core version of the script must be used instead of a custom version.
https://developer.wordpress.org/reference/functions/wp_enqueue_script/#default-scripts-included-and-registered-by-wordpress

[  ] All scripts and resources are included, no CDN or similar remote files are used.
    (The only exception is Google Fonts)

* Basic security

[  ] All customizer options, custom widgets and custom meta options are sanitized before saving.

[  ] All options are escaped before output.

[  ] Translated texts inside HTML attributes are escaped.

* PHP and JS errors

[  ] There are no PHP notices, warnings and errors on PHP version 5.6 -current.

[  ] There are no JS warnings or errors.

* Plugins

[  ] No plugins are required (Plugins may only be recommended, not required).

* Translations

[  ] All the text, including placeholders and default values, is translation ready.

* Screenshot

[  ] The screenshot is not a logo or a mockup, and is easy to be reproduced.

* Options

[  ] All options available in the customizer and as meta boxes or widgets have been tested and are working.

[  ] Enough documentation is included for custom front pages and similar to be easily set up.

* Readme file

[  ] The readme.txt file has been validated.
(https://wordpress.org/plugins/developers/readme-validator/)

* Accessibility

[  ] A Skip Link is included.
