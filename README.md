# Abandoned - Moved to [rewritten version in flask](https://github.com/grzesjam/SDIP-ZTM-parser)

# SDIP kzkgop to simple output

SDIP KZKGOP is tracking system for delays in city buses in Silesia (Without any API).

Pythons scripts which give easy to use API for any applications or just your own personal usage.

## Usage
SimOut.py - Simple output of delays 
```
 python3 internal.py [line]
```
htmlTable.py - output html code 
```
 python3 htmlTable.py [line]
```
internal.py - output line and SDIP internal number 
```
 python3 internal.py
```
jinternal .py - JSON output line and SDIP internal number 
```
 python3 jinternal.py 
```
jarrive.py - JSON output of times arrival to all bus stops  
```
 python3 jarrive.py [internalnumber]
```
jmain.py - JSON output of delays and most nessesary data  
```
 python3 jmain.py [line]
```



### Prerequisites

```
Python 3
```
```
Beautiful Soup
```
## Authors

* **Grzegorz M** - *Creator* - [SDIP-kzk-simple-output](https://github.com/grzesjam/SDIP-kzk-simple-output)

See also the list of [contributors](https://github.com/grzesjam/SDIP-kzk-simple-output/graphs/contributors) who participated in this project.

## License

This project is licensed under the **Mozilla Public License Version 2.0**
- see the [LICENSE.md](LICENSE) file for details
