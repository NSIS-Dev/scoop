# scoop-nsis

[![CircleCI](https://flat.badgen.net/circleci/github/NSIS-Dev/scoop-nsis)](https://circleci.com/gh/NSIS-Dev/scoop-nsis)
[![David](https://flat.badgen.net/david/dev/NSIS-Dev/scoop-nsis)](https://david-dm.org/NSIS-Dev/scoop-nsis?type=dev)

NSIS bucket for `scoop`, a command-line installer for Windows

## Prerequisites

Make sure to have [`scoop`](https://github.com/lukesampson/scoop#installation) installed before proceeding

## Installation

Add the NSIS bucket

```
scoop bucket add nsis https://github.com/NSIS-Dev/scoop-nsis
```

Install your preferred version of NSIS

```ps1
# Latest version
scoop install nsis/nsis

# Latest 2.x version
scoop install nsis/nsis-2

# Specific version
scoop install nsis/nsis-3.03
scoop install nsis/nsis-2.51
```

*“That's all Folks!”*
