# WhatsPy

Python Whatsapp API based on Selenium and ChromeDriver

> Working as of Mar 09 2020

## limitations

- All web.whatsapp.com limitations
- Scan QRCode on first run
- You must have a persons number saved to your phone
- You must set the contact exact and complete saved name
- Names must be unique in your contacts list

## QRCode scan

A PNG file is saved at local root directory as qrcode.png for scaning with yout phone. 
WhatsPy will try to save a profile so you don't need to scan the qrcode everytime.
Keep in mind that whatsapp logs you out if you try to login in multiple browsers.

## Chrome Install

WhatsPy uses a Chrome class that is just a wraper for the Selenum default implementation
that adds a few easy to use enhancements.

To use chrome with selenium you will need ChromeDriver.

A .whatspy directory will be added to your home directory to save chrome profile.

## Roadmap

- [x] Save QRCode image for scan
- [ ] Read latest chats
- [ ] Read latest messages from chat
- [x] Send message to contact by name (unique)
- [ ] Send message to contact by number
- [ ] Read latest archived chats
- [ ] Read latest archived messages from chat
- [ ] Archive chat
- [ ] Unarchive chat