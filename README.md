# TAK Preferences

This repository is an overview of different settings available for configuration in the `.pref` files of TAK.


# Overview

```xml
<?xml version='1.0' standalone='yes'?>
<preferences>
<preference version="1" name="cot_streams">
<entry key="count" class="class java.lang.Integer">1</entry>
<entry key="description0" class="class java.lang.String">_CN_ - TAK.SERVER</entry>
<entry key="enabled0" class="class java.lang.Boolean">true</entry>
<entry key="connectString0" class="class java.lang.String">_IPADDRESS_:8089:ssl</entry>
</preference>
<preference version="1" name="com.atakmap.app_preferences">
<entry key="clientPassword" class="class java.lang.String">atakatak</entry>
<entry key="caPassword" class="class java.lang.String">atakatak</entry>
<entry key="caLocation" class="class java.lang.String">cert/truststore-root.p12</entry>
<entry key="certificateLocation" class="class java.lang.String">cert/_CN_.p12</entry>
<entry key="displayServerConnectionWidget" class="class java.lang.Boolean">true</entry>
<entry key="atakControlOtherUserNotification" class="class java.lang.Boolean">false</entry>
<entry key="atakPluginScanningOnStartup" class="class java.lang.Boolean">true</entry>
<entry key="atakUpdateServerUrl" class="class java.lang.String">https://_IPADDRESS_/update</entry>
<entry key="appMgmtEnableUpdateServer" class="class java.lang.Boolean">true</entry>
<entry key="speed_unit_pref" class="class java.lang.String">1</entry>
<entry key="alt_unit_pref" class="class java.lang.String">1</entry>
<entry key="AgreedToEULA" class="class java.lang.Boolean">true</entry>
<entry key="locationTeam" class="class java.lang.String">Blue</entry>
<entry key="atakRoleType" class="class java.lang.String">Team Member</entry>
<entry key="enableNonStreamingConnections" class="class java.lang.Boolean">false</entry>
<entry key="pref_grid_type" class="class java.lang.String">MGRS</entry>
<entry key="deviceProfileEnableOnConnect" class="class java.lang.Boolean">true</entry>
<entry key="filesharingTransferTimeoutSecs" class="class java.lang.String">20</entry>

</preference>
</preferences>
```