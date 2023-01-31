# Manchester Java Community Website

This repository contains the source code for the Manchester Java Community that is hosted at https://manchesterjavacommunity.org.

 - JBake is used to develop the site, more information on this tool can be found at https://jbake.org
 - Bulma is the CSS framework used, read more at https://bulma.io

Please check for current issues and existing PRs; we will probably accept drive-by pull requests but someone might already be working on something.

## How to build the site

**Required:**
 - Git
 - Java 8+

### Install JBake

**Unix**

```bash
curl -s "https://get.sdkman.io" | bash
sdk install jbake
```

**Windows**
 - Download from https://jbake.org/download.html
 - Create directory $JBAKE_HOME
 - Add $JBAKE_HOME/bin to PATH variable

### Build and launch the site

Clone the repo:
```
git clone https://github.com/ManchesterJavaCommunity/manchesterjavacommunity.github.io.git
```

Make your amazing changes.

Build the site.

```bash
jbake -b
```

Serve up the content to check all okay; will start a webserver on http://localhost:8820.

```bash
jbake -s
```

Further excellent documentation for JBake can be found at https://jbake.org/docs/latest.
