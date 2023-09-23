# AI AccessTools

This software repository is specifically accessibility focused.

AI AccessTools is an Open Source collection of tools used for AI Automation.  Automation is defined as anything to automate anything. The goal here is to begin collecting resources to help provide services to those in need of automation.  The tools created in this repository will be based on work from other Open Source repositories or custom code.  Here we will simply assemble existing technologies into unique and helpful ways.

## Ideas for projects here

### Chrome Commander

A voice interface to a NodeJS app which provides a voice interface for interacting with websites.  This is not a 'general' tool in which any website can be voice navigated, the navigation commands will be specific to individual websites.  This allows a tool which becomes much more flexible and easy for the user when at Capital One website the interaction becomes

"Login use saved credentials"
"Navigate billing"
"View bill"
"Pay bill"
"Logout"

...versus using head movements to control a mouse cursor to click through the Capital One website.

This can be done using existing browser automation software called Puppeteer and creating voice modules (?) for command recognition.  But I know frameworks exist to create this technology.

The creation of the scripts to automate the websites will be tedious, error prone, and subject to continuous testing and upkeep as every time a websites makes an update it can break the existing automation script.

Once released an in use for a select site, requests for additional sites to be automated will come in.  I would suggest that once established, it would be possible to seek funding from websites to add themselves to our list of supported sites.

### AWS Cloud Administration

A voice interface to a NodeJS app which provides a voice interface for interacting with AWS CLI Cloud Administration.

A CLI is a Command Line Interface.  Is is the real workhorse of system administration.  Clouds have web interfaces, but those are for the noob admins.  Everything can be done with a system utilizing it's CLI's and every major online system has a CLI.

My idea is to open this world of CLI's to the hands free community of the online world.

I believe this would open system administration jobs to those utilizing computers in a hands free manner.

The technology exists to create such a voice interface.  I believe it's important here to create and own the 'standard' voice interface to interacting with these commercial CLI's.  Such patented functionality would include interacting with a voice cache - a clipboard on steroids - like oh-my-zsh for the clipboard allowing the user to easily save fragments and use later, easily making voice macros on the fly.