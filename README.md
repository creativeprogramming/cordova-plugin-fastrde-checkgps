# phonegap-checkGPS
Plugin to Check if GPS enabled on iOS and Android

## install
```
yourAppDir$ cordova plugin add https://github.com/creativeprogramming/cordova-plugin-fastrde-checkgps.git
```

## usage

```javascript
CheckGPS.check(function(){
    //GPS is enabled!

  },
  function(){
    //GPS is disabled!

  });
```
