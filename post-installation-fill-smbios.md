# Post installation: fill SMBIOS info

- Fill `SMBIOS` and `RtVariables` sections with more details(You should use Clover Configurator to generate these values). The `MLB` value in `RtVariables` should be same as `BoardSerialNumber` in `SMBIOS`.

```xml
<key>RtVariables</key>
<dict>
    <key>BooterConfig</key>
    <string>0x28</string>
    <key>CsrActiveConfig</key>
    <string>0x3E7</string>
    <key>MLB</key>
    <string>C026532704NJ0PGUX</string>
    <key>ROM</key>
    <string>UseMacAddr0</string>
</dict>
<key>SMBIOS</key>
<dict>
    <key>BiosReleaseDate</key>
    <string>09/28/2018</string>
    <key>BiosVendor</key>
    <string>Apple Inc.</string>
    <key>BiosVersion</key>
    <string>IM183.88Z.F000.B00.1809280842</string>
    <key>Board-ID</key>
    <string>Mac-BE088AF8C5EB4FA2</string>
    <key>BoardManufacturer</key>
    <string>Apple Inc.</string>
    <key>BoardSerialNumber</key>
    <string>C026532704NJ0PGUX</string>
    <key>BoardType</key>
    <integer>10</integer>
    <key>BoardVersion</key>
    <string>1.0</string>
    <key>ChassisAssetTag</key>
    <string>iMac-Aluminum</string>
    <key>ChassisManufacturer</key>
    <string>Apple Inc.</string>
    <key>ChassisType</key>
    <string>0x09</string>
    <key>EfiVersion</key>
    <string>166.0.0.0.0</string>
    <key>Family</key>
    <string>iMac</string>
    <key>FirmwareFeatures</key>
    <string>0xFC0FE137</string>
    <key>FirmwareFeaturesMask</key>
    <string>0xFF1FFF3F</string>
    <key>LocationInChassis</key>
    <string>Part Component</string>
    <key>Manufacturer</key>
    <string>Apple Inc.</string>
    <key>Mobile</key>
    <false/>
    <key>PlatformFeature</key>
    <string>0x00</string>
    <key>ProductName</key>
    <string>iMac18,3</string>
    <key>SerialNumber</key>
    <string>C02T11Y2J1GJ</string>
    <key>SmUUID</key>
    <string>8D1BC6CB-2795-40BA-8A6E-31032614F288</string>
    <key>Version</key>
    <string>1.0</string>
</dict>
```
