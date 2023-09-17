This is an obfuscation technique that evades static detection by converting the payload bytes into IPv4 or IPv6 strings.

For example, we have the bytes `0xD5, 0x48, 0x83, 0xC4, 0x28, 0x3C, 0x06, 0x7C, 0x0A, 0x80, 0xFB, 0xE0, 0x75, 0x05, 0xBB, 0x47`.

In IPv4Fuscation, we use every 4 bytes to make a single IPv4 string. Each byte represents an octect, where we convert it from hex to decimal. In our example bytes, if we use the first four, we get the string `213.72.131.196`

In IPv6Fuscation, it would be every 16 bytes for an IPv6 address. Here those bytes would be `D548:83C4:283C:067C:0A80:FBE0:7505:BB47`