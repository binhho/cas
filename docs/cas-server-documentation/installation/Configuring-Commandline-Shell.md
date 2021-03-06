---
layout: default
title: CAS - Configuring Shell
---

# CAS Command-line Shell

The CAS command-line shell provides the ability to query the CAS server for help on available settings/modules and
various other utility functions.The shell engine is presented as both a CLI utility and an interactive shell.

To invoke and work with the utility, simply execute:

```bash
java -jar /path/to/cas-server-support-shell-$casVersion.jar
```

...where `$casVersion` needless to say is the CAS version that is deployed.

The interface that is next presented will guide you through with available parameters and methods of querying.
Using the same approach, you will also learn how to launch into the interactive shell and query the CAS
engine dynamically.

Note that the [WAR Overlay deployment strategy](Maven-Overlay-Installation.html) should already be equipped with this functionality. You should not have to do anything special and extra to interact with the shell. See the relevant overlay documentation for more info on how to invoke and work with the shell.