# UEFIReader
Tool to generate .inf payloads for use in various other UEFI projects out of an existing UEFI volume

## Building guide for Linux (Tested only Ubuntu 22.04 Docker) 
Install .NET SDK
```
apt update
apt install dotnet-sdk-8.0
```

Building
```
cd UEFIReader/
dotnet build UEFIReader.sln
```

Where is binary?

Under "UEFIReader/bin/Debug/net8.0" of the project root.
