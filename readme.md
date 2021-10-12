# @huyandong/netease-nim-web-sdk

[![npm version](https://badge.fury.io/js/@huyandong%2Fnetease-nim-web-sdk.svg)](https://badge.fury.io/js/@huyandong%2Fnetease-nim-web-sdk)
# 网易云信 web sdk
同步官方web sdk
## Install 
```nodejs
npm install @huyandong/netease-nim-web-sdk
```
## Usage
``` javascript

import { 
    NIM_Web_Chatroom,
    NIM_Web_Netcall,
    NIM_Web_NIM,
    NIM_Web_NRTC,
    NIM_WEB_SDK,
    NIM_Web_WebRTC,
    NIM_Web_WhiteBoard,
    SDK_VERSION } from "@huyandong/netease-nim-web-sdk";

const nim = NIM_Web_NIM.getInstance({...});
// 其他用法同步官方
```