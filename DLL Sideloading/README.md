This is a simple DLL sideloading example in Rust.  

Windows Defender's MpCmdRun.exe and NisSrv is vulnerable to DLL sideloading, where arbitrary code can be executed through the exe with a malicious `mpclient.dll`. Although vendors have patched this already, older versions are still vulnerable. This example was done as an educational example.  

Related resources:
- [Hijack Libs](https://hijacklibs.net)
