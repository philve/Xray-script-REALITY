# Xray-REALITY Management Screenplay

* A pure shell-written REALITY management script
* USE THE VLESS-XTLS-UTLS-REALITY CONFIGURATION
* Implement self-filling of the Xray listening port
* You can customize the input UUID, and non-standard UUIDs will be mapped to UUIDv5 using Xray uuid -i "Custom Strings"
* Implement DEST selection and self-filling
    - Implement TLSv1.3 and H2 validation for self-filled dest
    - Implement automatic acquisition of serverNames with self-filled dest
    - Implement the filtering of automatically obtained serverNames wildcard domain names and CDN SNI domain names, and dest will automatically add it to serverNames if it is a subdomain
    - Customize the display of spiderX that implements self-filling dest, for example: client config is displayed when self-filling dest is fmovies.to/homespiderX: /home
* By default, you can disable traffic, advertising, and BT
* Implement automatic updates of geo files


## How to use

* wget

  ```sh
  wget --no-check-certificate -O ${HOME}/Xray-script.sh https://raw.githubusercontent.com/zxcvos/Xray-script/main/reality.sh && bash ${HOME}/Xray-script.sh
  ```

* curl

  ```sh
  curl -fsSL -o ${HOME}/Xray-script.sh https://raw.githubusercontent.com/zxcvos/Xray-script/main/reality.sh && bash ${HOME}/Xray-script.sh
  ```

## Script interface

```sh
--------------- Xray-script ---------------
Version : v2023-03-15(beta)
Description : Xray management script
----------------- Load Management ----------------

  1. Install
  2. Update
  3. Uninstall
----------------- Operation Management ----------------
  4. Start
  5. Stop
  6. Restart
----------------- Configuration Management ----------------
101. View Configuration
102. Statistics
103. Modify ID
104. Modify Destination
105. Modify x25519 Key
106. Modify ShortIDs
107. Modify Xray Listening Port
108. Refresh Existing ShortIDs
109. Add Custom Short IDs
----------------- Other Options ----------------
201. Update to Latest Stable Kernel
202. Uninstall extra kernels
203. Modify SSH Port
204. Network Connection Optimization
-------------------------------------------
```

## Client configuration

| Name | Value |
| :--- | :--- |
| address | IP or domain name on the server side |
| Port | 443 |
| UUID | xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx |
| Flow control | xtls-rprx-vision |
| Transport Protocol | tcp |
| Transport Layer Security	 | reality |
| SNI | learn.microsoft.com |
| Fingerprint | chrome |
| PublicKey | wC-8O2vI-7OmVq4TVNBA57V_g4tMDM7jRXkcBYGMYFw |
| shortId | 6ba85179e30d4fc2 |
| spiderX | / |

## Thanks

[Xray-core][Xray-core]

[REALITY][REALITY]

[chika0801 Xray 配置文件模板][chika0801-Xray-examples]

[Xray-core]: https://github.com/XTLS/Xray-core (THE NEXT FUTURE)
[REALITY]: https://github.com/XTLS/REALITY (THE NEXT FUTURE)
[chika0801-Xray-examples]: https://github.com/chika0801/Xray-examples (chika0801 Xray 配置文件模板)

**This script is for communication and learning purposes only, please do not use this script to do anything illegal. Where the Internet is illegal, illegal things will be punished by law.**
