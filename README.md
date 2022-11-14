# TAK Preferences

This repository is an overview of different settings available for configuration in the `.pref` files of TAK.


# Usage
The preference file (`.pref`) should have the following layout:

<?xml version='1.0' standalone='yes'?>
<preferences>
    <preference version="1" name="cot_streams">
        <entry key="" class="">VALUE</entry>
    </preference>
    <preference version="" name="com.atakmap.app_preferences">
        <entry key="" class="">VALUE</entry>
    </preference>
</preferences>

Preferences not in use (for example `cot_streams`) can be left out of the `.pref` file.

# cot_streams

| Entry Key                                                                                | Value   | Usage                                            | ATAK | WINTAK | ITAK |
| ---------------------------------------------------------------------------------------- | ------- | ------------------------------------------------ | ---- | ------ | ---- |
| <entry key="count" class="class java.lang.Integer">1</entry>                             |         |                                                  |      |        |      |
| <entry key="description0" class="class java.lang.String">TAKSERVER</entry>               | String  | Sets the server connection name                  | X    | X      |      |
| <entry key="enabled0" class="class java.lang.Boolean">true</entry>                       | Boolean | If the server connection is enabled              | X    | X      |      |
| <entry key="connectString0" class="class java.lang.String">192.168.0.15:8089:ssl</entry> | String  | IP + Port + connection type of server connection | X    | X      |      |


# com.atakmap.app_preferences

| Entry Key                                                                                          | Value   | Usage                           | ATAK | WINTAK | ITAK |
| -------------------------------------------------------------------------------------------------- | ------- | ------------------------------- | ---- | ------ | ---- |
| <entry key="clientPassword" class="class java.lang.String">atakatak</entry>                        | String  | Password for client certificate | X    | X      |      |
| <entry key="caPassword" class="class java.lang.String">atakatak</entry>                            | String  | Password for server certificate | X    | X      |      |
| <entry key="caLocation" class="class java.lang.String">cert/truststore-root.p12</entry>            | Path    | Location of server certificate  | X    | X      |      |
| <entry key="certificateLocation" class="class java.lang.String">cert/_CN_.p12</entry>              | Path    | Location of client certificate  | X    | X      |      |
| <entry key="displayServerConnectionWidget" class="class java.lang.Boolean">true</entry>            | Boolean |                                 |      |        |      |
| <entry key="atakControlOtherUserNotification" class="class java.lang.Boolean">false</entry>        | Boolean |                                 |      |        |      |
| <entry key="atakPluginScanningOnStartup" class="class java.lang.Boolean">true</entry>              | Boolean |                                 |      |        |      |
| <entry key="atakUpdateServerUrl" class="class java.lang.String">https://_IPADDRESS_/update</entry> |         |                                 |      |        |      |
| <entry key="appMgmtEnableUpdateServer" class="class java.lang.Boolean">true</entry>                | Boolean |                                 |      |        |      |
| <entry key="speed_unit_pref" class="class java.lang.String">1</entry>                              |         |                                 |      |        |      |
| <entry key="alt_unit_pref" class="class java.lang.String">1</entry>                                |         |                                 |      |        |      |
| <entry key="AgreedToEULA" class="class java.lang.Boolean">true</entry>                             | Boolean |                                 |      |        |      |
| <entry key="locationTeam" class="class java.lang.String">Blue</entry>                              |         | Sets team (color)               |      |        |      |
| <entry key="atakRoleType" class="class java.lang.String">Team Member</entry>                       |         | Sets team role                  |      |        |      |
| <entry key="enableNonStreamingConnections" class="class java.lang.Boolean">false</entry>           | Boolean |                                 |      |        |      |
| <entry key="pref_grid_type" class="class java.lang.String">MGRS</entry>                            |         |                                 |      |        |      |
| <entry key="deviceProfileEnableOnConnect" class="class java.lang.Boolean">true</entry>             | Boolean |                                 |      |        |      |
| <entry key="filesharingTransferTimeoutSecs" class="class java.lang.String">20</entry>              |         |                                 |      |        |      |
