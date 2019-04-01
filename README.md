# deluge-mobile
Deluge Web-UI for Phones

Made and testet with Deluge Web UI 1.3.12 and nginx


Add the following to your deluge block to apply the style
```
proxy_set_header Accept-Encoding "";
sub_filter '</head>' '<link rel="stylesheet" type="text/css" href="https://lanjelin.github.io/deluge-mobile/mobile.css"><meta name="viewport" content="width=device-width, initial-scale=1"></head>';
sub_filter_once on;
```
