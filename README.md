# uberbecue_loopback
Backend of Uberbecue


> A loopback project

## Build Setup

``` bash
# install dependencies
npm install

# loopback install
npm install -g loopback-cli

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

Loopback api running on port localhost:3000

Loopback api:Kaan Karanlik
Documentation Loopback:Denis Peinlich

grill.js
export of module grill function.

grill.json
Placeholder properties and placeholder, methods, Condition and so on.

message.js
Export of message function, technical function of message function to receiver.


message.json
Placeholder for array to read values with strings http request over get method.

uberbecue_lb server folder

component-config.json
Path for mounting the explorer view of the loopback data integration.

config.json
configuration of the api including applying port (3000) error handler integration.
No script integration in json (prevents hacking as well as jscript injection)
limit of file 100kb, activation of url encoding. Closing of Session if
sensitive changes are made (hacking prevention)

datasource.json
databse integration and connector.


middleware.development.json
Integration of error handler for debugging and logging.


middleware.json
initialisation of loopback, setting of credentials and maximum age,

model-config.json


server.js

boot folder

authentication.js

root.js
