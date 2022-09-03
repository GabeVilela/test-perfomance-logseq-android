# test-perfomance-logseq-android
This is a [Logseq](https://github.com/logseq/logseq) graph folder, built based on my own personal graph, but with fewer pages, and with every information replaced with `lorem ipsulum`.  
**The purpose of this repo is to test Logseq's Android app loading times after clicking on "BENCHMARK MOC", in the right sidebar > Contents.**

## My benchmark results
## Methodology
I did 3 runs. In each run, the loading time were measured twice:
- right after opening the app
- after going back to journals and re-opening the benchmark page.
### Results
Logseq version 0.8.4  
**All times mentioned below were measured by hand, so please, consider a margin of error up to 30ms**
| Test | 1st run | 2nd run | 3rd run |
| --- | --- | --- | --- |
| After opening app from closed state | 5s and 40ms | 5s and 41ms | 5s and 63ms |
| After going back to journals | 4s and 02ms | 4s and 01ms | exactly 4s |

> _Just for comparison, Obsidian 1.3.1 takes approximately 83ms to open the same page, using the same folder as vault_
### Device used in the benchmark
- Manufacturer: Samsung
- Model name: Galaxy Tab A7
- Model number: SM-T505
- Tech specs
  - CPU: Qualcomm Snapdragon 665 2.02GHz
  - GPU: Adreno 610 950MHz
  - RAM: 2705 MB
  - OS: Android 12
      - API Level: 31
      - Kernel architecutre: aarch64