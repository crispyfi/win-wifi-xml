# win-wifi-xml
Generates an XML file for Windows 11 Wi-Fi Authentication to be deployed using an Intune Custom Configuration Profile using the following OMA-URI:
`./Vendor/MSFT/WiFi/Profile/<SSID Name>/WlanXml`

Configuration includes:
- TEAP (optional)
  - Outer identity of 'anonymous'
  - EAP-TLS for both inner-methods
- EAP-TLS
- WPA3-Enterprise 192-bit mode (Optional)
- Server Certificate validation
- Prompt to authorize new servers disabled
- Simple Certificate selection with 'Client Authentication' EKU and specific Issuing CA

[Click here to access live version](https://wifi-xml.crispyfi.com)
