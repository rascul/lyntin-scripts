---
title: target
layout: default
---

Targetting aliases. Supports up to 10 different targets, and a primary target
that will get set to the last used target.

### Load the script

Requires the ifvar module.

`#read scripts/target`

### Aliases

* `k0` through `k9` - Kill targets 0 through 9 and set primary target.
* `kk` - Kill primary target.
* `t0` through `t9` - View or set targets 0 through 9.
* `target` - View or set primary target.
* `targets` - View all defined targets.

### Variables

* `$t0` through `$t9` - Holds the various numbered targets.
* `$target` - Holds the primary target.

