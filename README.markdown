# Google Plus status update bot

* Author: Luka Pusic <luka@pusic.si> (lukapusic on github)
* URI: http://360percents.com/posts/first-google-google-plus-status-update-bot-in-php/

## Description
This bot can log into your Google account and update your Google Plus status,
but you can extend it to other Google products. All this is done without Google API,
OAuth, tokens or any other annoying products.

## System requirements
* PHP curl extension

## Instructions
1. Open gplus.php and edit email and password
2. run it ```php gplus.php```

## Changelog

#### Mar 9 2012
* status is now passed as command line argument instead of directly in a variable declaration inside the script
* PHP hashbang for easier command line usage

#### Nov 11 2011
* added debug parameter, pageid parameter, pc_uagent parameter
* page updating still not implemented

#### Nov 16 2011
* changed the way baseurl is determined, google removed base href

#### Dec 15 2011
* post visibility is not public by default

#### Mar 2 2012
* fixed "&" encoding (thx Pauly)

## Known issues
* fails if you didn't confirm mobile location terms and conditions
* fails if you have mobile verification enabled

## TODO
* add an option to change post visility
* add posting to pages

## License
 ----------------------------------------------------------------------------
 "THE BEER-WARE LICENSE" (Revision 42):
 <luka@pusic.si> wrote this file. As long as you retain this notice you
 can do whatever you want with this stuff. If we meet some day, and you think
 this stuff is worth it, you can buy me a beer in return. Luka Pusic
 ----------------------------------------------------------------------------
