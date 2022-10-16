# Not Maintained
This is a relict and Example Implementation of a NFC Scanner connected via a Websockets API Using the Feathers Framework

## Update will turn that into a Markdown Based Guide 
how to create a NodeJS Application that uses a **ACR122 USB reader** but it should work with **all PC/SC compliant devices**

```shell
npm i .....
```

Implement Reader hardware via Posix Methods and Event Emitters so linking fileDescriptors and implement the main Reader Protocol.

This example used feathers to abstrack IPC and RPC Handling via a external exposed API. Today we would prefer to use raw net sockets and JSON as RPC. 
To send Binary Data eg none C UTF-8 including 0x00 bytes as array of integers inside the json. the JSON Parse Method will turn it back into byte buffer view without overhead. 



# feathers-nfc-pcsc
A feathers js Service using pcsc bindings.

Built-in support for auto-reading **card UIDs** and reading tags emulated with [**Android HCE**](https://developer.android.com/guide/topics/connectivity/nfc/hce.html).

> **NOTE:** Reading tag UID and methods for writing and reading tag content **depend on NFC reader commands support**.
It is tested to work with **ACR122 USB reader** but it should work with **all PC/SC compliant devices**.  
When detecting tags does not work see [Alternative usage](#alternative-usage).

This library uses pscslite native bindings [pokusew/node-pcsclite](https://github.com/pokusew/node-pcsclite) under the hood.
[pokusew/nfc-pcsc](https://github.com/pokusew/nfc-pcsc)
