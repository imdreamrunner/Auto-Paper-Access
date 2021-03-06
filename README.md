# Auto-Paper-Access
A simple script runs on Tampermonkey. You can easily access IEEE Xplore, ACM Digital Library, etc without clicking proxy bookmarklet provided by universities.

### Usage
1. Install [Tampermonkey](https://tampermonkey.net/) plugin for your web browsers.

2. Install this script from https://openuserjs.org/scripts/lushl9301/Auto_Paper_Access by simply click *install*

3. Done! And you can try the following papers from ACM DL and IEEE Xplore:

    [Mars: a MapReduce framework on graphics processors](http://dl.acm.org/citation.cfm?id=1454152&CFID=727506701&CFTOKEN=12709622)

    [Multikernel Data Partitioning With Channel on OpenCL-Based FPGAs](http://ieeexplore.ieee.org/document/7857086/)

### Supported Universities
* National University of Singapore
* Nanyang Technological University, Singapore

### Known Issues
* Need to allow unsafe javascript execution on https://link.springer.com

* Need to remove [//@run-at document-start](https://github.com/lushl9301/Non-Click-NUS-Library-Proxy/blob/master/Non-Click.user.js#L9) for https://link.springer.com

### Contributor
* [lushl9301](https://github.com/lushl9301), National University of Singapore
* [koallen](https://github.com/koallen), Nanyang Technological University, Singapore
