---
layout: post
title: Control a Servo with Raspberry Pi and Pimoroni Explorer Hat
tags: [raspberry]
---

## Draft

Why Explorer Hat?

### Step 1: find a c-libary to control a servo

[ServoBlaster](https://github.com/richardghirst/PiBits/tree/master/ServoBlaster)

```bash
$ sudo ./servod --p1pins=31 --invert
$ echo 0=120 > /dev/servoblast
```
