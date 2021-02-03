# hms-ads-identifier-cordova
Based on https://github.com/HMS-Core/hms-cordova-plugin/tree/master/cordova-plugin-hms-ads

This plugin can be used if you want to access the Huawei's OAID. It ads the required 'com.huawei.hms:ads-identifier' package.

You might need to add this to proguard:
```
-keep interface com.huawei.hms.ads.**{*;}
-keep class com.huawei.openalliance.ad.**{*;}
```
