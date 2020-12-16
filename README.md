# ble-services-nrf-connect
The `nRF Connect` mobile application supports import and export of BLE services. Some of the examples within the nRF SDK require GATT server (central device) for demonstration purpose. In such case `*.ncs` may be found within the application example folder itself.

However the `.ncs` file is supported by Desktop version. For the mobile version `XML` file is used. One such example is the `Current Time Service` client application with `ble_app_cts_c/cts_central.ncs` file. The `Configure GATT server` in the menu allows to import XML files alone.

**Note:**
You can export the `Sample configuration` from `Configure GATT server` in the menu and view it a text editor to understand and write one by yourself. I viewed the `cts_central.ncs` file and compared it with the CTS specification to write the XML file.

### Following services in XML format are available:
1. Current Time Service (GATT Server)