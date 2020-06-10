# MFTECmd

MFT parser for NTFS file systems

Open Source Development funding and support provided by the following contributors: [SANS Institute](http://sans.org/) and [SANS DFIR](http://dfir.sans.org/).

## How to build and run on MacOS

TLDR:

```
brew cask install dotnet-sdk
git clone https://github.com/lctrcl/MFTECmd
cd MFTECmd
dotnet restore
dotnet build --configuration=release
dotnet MFTECmd/bin/Release/netcoreapp2.2/MFTECmd.dll --f /path/to/\$MFT --csv /path/to/csv/
```
