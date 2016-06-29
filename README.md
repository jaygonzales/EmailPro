# EmailPro

Email module for FileMaker Pro

## Overview

FileMaker’s Send Mail script step allows you to send plain text emails through SMTP or the user’s mail client. You need to look beyond native functionalities if you’d like to use HTML formatting or send multiple attachments. HTML-formatted emails in particular can provide some fantastic polish to your solutions.

There are some great email plug-ins out there, but sometimes I don’t think my needs justify the cost. This module handles the following scenarios free of cost:

- HTML-formatted content
- Multiple attachments
- SMTP authenticate over SSL/TLS
- Multiple To, CC and/or BCC recipients
- Custom From and Reply-To headers
- Server-side compatible

## Usage

Just call the “. emailPro . send” script. It takes its parameters in [Let format](http://www.modularfilemaker.org/documentation/#Passing_Parameters). If you prefer to use a different parameter format, please see the [ParamConverter](http://www.modularfilemaker.org/2013/11/paramconverter/) module for an easy bridge between formats.

See the README script for more information on testing and customizing your implementation.

## Requirements

- FileMaker 13 or higher, Pro or Server
- [bBox plug-in](http://www.beezwax.net/bbox) (Free)
- macOS

bBox is only compatible with OS X. If you can find a plug-in to execute Python scripts, you might be able to make it work.

## Installation

Just find a place to store the plug-in file in your solution, import the module scripts, and customize the Configuration and Settings scripts.

If you will be using gmail for sending messages, be sure to review [Allow less secure apps to access accounts](https://support.google.com/a/answer/6260879). This is required due to the inability to use Google's two-step verification for sender.

## Download and Installation

Use the "Clone or download" button on the [GitHub page](https://github.com/beezwax/EmailPro), then "Download ZIP". In the resulting EmailPro folder,  open the EmailPro.fmp12 file. Its README script contains installation instructions.

## Contact

Beezwax Datatools, Inc.
info@beezwax.net
