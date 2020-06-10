# MFTECmd

MFT parser for NTFS file systems

Open Source Development funding and support provided by the following contributors: [SANS Institute](http://sans.org/) and [SANS DFIR](http://dfir.sans.org/).

### Ported from EricZimmerman to .netcoreapp2.2 so it can be run on Linux 

#### Benchmark - 1.3GB MFT
###### MFTECmd - Linux 
Run time 29.9044 seconds
FILE records found: 708,597 (Free records: 408,323) File size: 1.1GB

###### AnalyseMFT - Linux 
Run time 1219 seconds

```
dotnet restore
dotnet build -r linux-x64
```
