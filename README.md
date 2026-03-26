## HuskyFPV: New Generation Digital FPV system
HuskyFPV team is committed to providing a new generation of powerful and reliable digital FPV systems. It breaks through the limitations of conventional technological frameworks by adopting an underlying engine with multi-aggregation capabilities, which will no longer be limited to physical distances or simple video function.

## Features
HuskyFPV has the following features:

- Digital video transmission latency is as low as 48ms
- Aggregating telemetry, rc signal, and video streams for simultaneous transmission
- User-configurable colored OSD layout
- Racing-grade video encoding algorithms maintain clear imagery even at speeds up to 350 km/h
- Dual video source simultaneous transmission support
    - each video stream can be accessed via the RTSP protocol through the ethernet or wlan interface of the ground unit
    - First video source (use ethernet): rtsp://192.168.1.231:8554/1
    - Second video source (use ethernet): rtsp://192.168.1.231:8555/1
    - First video source (use wlan): rtsp://192.168.110.1:8554/1
    - Second video source (use wlan): rtsp://192.168.110.1:8555/1
- Advanced video aggregation acceleration technology ensures smooth, stable display for multiple video streams with minimal latency
- Users can customize external RTSP addresses to connect to multiple devices (gimbals, IP cameras, etc)
    - URL format: rtsp://username:password@ip:port/path
    - Encoder format: H.265
    - Resolution: max 1080p30
	- Note: RTSP digest authentication is not supported.
    - Tested models:
        - SIYI ZR10, ZR30, A8-mini, A2-mini
        - Skydroid C10/PRO, C12
        - TOPOTEK
        - XF Z1-mini, D-80Pro
        - SudoCam H200 (https://item.taobao.com/item.htm?id=708237932971)
        - MC-A81/A85 (http://item.taobao.com/item.htm?id=738107142074)
        - MC-800S5 (https://item.taobao.com/item.htm?id=865561621758)
        - FH81-PRO (https://item.taobao.com/item.htm?id=756965128386)
        - IPC H54 (https://item.taobao.com/item.htm?id=838306416275)
        - IPC H44 (https://item.taobao.com/item.htm?id=1003120164322)
        - IPC H41 (https://item.taobao.com/item.htm?id=675451083033)
- Video output supports Picture-in-Picture (PIP) display
- Supports switching the Picture-in-Picture (PIP) video via the 'M' button, or by an S.BUS channel configured in the "RC Function Mapping" menu.
- Supports configuring PWM output parameters of air unit, inclue scale factor and reverse.
- Support for STUN servers allows devices to establish P2P connections over the Internet.
- Support for TURN servers allows devices to establish RELAY connections over the Internet when P2P connections are unavailable.

## Hardware
- Supported Models:
	- V4 Pro Hyper Fusion Transmitter
- Supported 5.2/5.8GHz wireless module:
	- B-Link M8812EUx
- Supported LTE Cat4 module:
	- Quectel EM05-G, EM05-CN, EC200A
 	- Simcom SIM7600G-H, A7600C

<!--
- Provides schematics, allowing users to unleash their creativity in design

- Soc support:
	- sigmastar SSC378
 	- sigmastar SSR621Q

-->
