# MFTECmd

MFT parser for NTFS file systems

Open Source Development funding and support provided by the following contributors: [SANS Institute](http://sans.org/) and [SANS DFIR](http://dfir.sans.org/).

##### Ported from EricZimmerman to .netcoreapp2.2 so it can be run on Linux 

#### Benchmark

#### MFTECmd - Linux 
| MFTECmd - Linux    | Result                          |
|--------------------|--------------------------------|
| File size          | 469.5MB                        |
| Run time           | 12.0830 seconds                |
| FILE records found | 392,879 (Free records: 87,835) |
| Lines produced     | 580,417                        |

#### AnalyseMFT - Linux 
| AnalyseMFT     | Result                    |
|----------------|--------------------------|
| File size      | 469.5MB                  |
| Run time       | 2 minutes 21.058 seconds |
| Lines produced | 482,207                  |

### Building
```
dotnet restore
dotnet build -r linux-x64
```
