---
layout: post
title:  "Kiire, kerge ja paindlik operatsioonisüsteem SparkyLinux"
categories: [tech, linux]
---

# Mis on SparkyLinux?

SparkyLinux on Debian operatsioonisüsteemil põhinev GNU/Linuxi distributsioon.

Sparky on kiire, kerge ja täielikult kohandatav operatsioonisüsteem, mis pakub erinevaid versioone erinevateks kasutusjuhtudeks. [1]


# Live USB

Tõmba alla **.iso** fail (LXQt amd64) [2] ja installi **UNetBootin** [3]

```
diskutil list
brew cask install --appdir="/Applications" unetbootin
```

# Käivita tööjaam

Pane USB-seade sihtmasinasse ja käivita. Vajuta kohe F12, et siseneda alglaadurisse ning buudi süsteem USB-seadmelt.


# Allikad

<ul style="list-style-type:none;">
  <li>
    [1] <a href="https://sparkylinux.org/">https://sparkylinux.org/</a>
  </li>
  <li>
    [2] <a href="https://sparkylinux.org/download/stable/">https://sparkylinux.org/download/stable/</a>
  </li>
  <li>
    [3] <a href="https://www.sysgeeker.com/burn-iso-to-usb-on-mac.html">https://www.sysgeeker.com/burn-iso-to-usb-on-mac.html</a>
  </li>
</ul>

