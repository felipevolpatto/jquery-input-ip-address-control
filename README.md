jquery-input-ip-address-control
===============================

Plugin controls the format of IPv4 or IPv6 addresses (BETA).

## Overview
An Ip address controller.
During user input field, this plugin controls the format of IPv4 or IPv6 addresses.

## Example

``` javascript
$(function(){
    $('.ipv4').ipAddress();
    $('.ipv6').ipAddress({v:6});
});

//mask input type text (ipv4) : ___.___.___.___
//mask input type text (ipv6) : ____:____:____:____:____:____:____:____
```

## Helpers

``` javascript
var myip = '192.168.1.1';
if(myip.isIpv4()) { // or myip.isIpv6()
    return true;
} else {
    return false;
}
```

## Credits
https://code.google.com/p/jquery-input-ip-address-control/
