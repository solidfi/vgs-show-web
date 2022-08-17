# web-vgs
Web based Solid-VGS integration sample code

## Table of contents

- [Overview](#overview)
- [Run the app](#run-the-app)
- [Parameters](#Parameters)

## Overview
The purpose of this app is to show how to use the VGS Show JavaScript SDK. For complete information about the API, head to the [docs](https://www.verygoodsecurity.com/docs/vgs-show).

## Run the app
To Run the app run `npx serve`. then open `http://localhost:5000` in browser.

or run the html files under a local webserver(wamp, lamp, xampp...), openning the file directly in browser will not work due to CORS.


## Parameters
| Parameters          | Description   |
| -------------       | ------------- |
| VGS-Organization-ID | vgs organization id |
| VGS-Vault-ID        | vgs vault id |
| card-Id             | solid card id |
| show-token          | Show token you can get it from api |

Note: The VGS Org and vault ID's required for implementing the sample code can be requested via a Solid help desk ticket.
