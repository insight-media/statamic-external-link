# Link Fieldtype for Statamic

This is a simple Fieldtype for Statamic 3, created to handle links. 

![Link Fieldtype](link_fieldtype.png "Link Fieldtype")

## What can it do?

- It does add a test me button to the field, so you can instantly test if the link is correct
- It will prepend https:// to the url to make sure, that the url is working correctly if inserted on the page as a link
- It will remove http and replace it with https, so that you can be sure to have only secure links on your site

This fieldtype is especially helpful, in case you do work with very long links. One case could be ticket sales links, which tend to be very long. 

## Installation 

This Fieldtype works with **Statamic 3** only!

Install it via the composer command
```
composer require jonassiewertsen/link-fieldtype
```

Does the Fieldtype does not show up? Rebuild your addon package manifest and clear your cache
```
php please addons:discover
php please cache:clear
```

Have fun!