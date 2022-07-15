# Manchester Java User Group Website

### This repository contains the source code for the Manchester JUG community that is hosted at https://manchesterjavacommunity.org/

### The site uses JBake to develop the site, more information on this tool can be found at https://jbake.org/

## How to build the site

### Install JBake
#### ==============
```bash
curl -s "https://get.sdkman.io" | bash
```
```bash
sdk install jbake
```
### Launch the site
#### =================
Once the repo is cloned and moved into we can launch the site with the following command
```bash
jbake -b -s
```
The site will then be available at http://localhost:8820/
