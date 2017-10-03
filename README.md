```Assembly
    ____  _               _      __
   / __ \| |__  _   _ ___| |_   / /
  / / _` | '_ \| | | / __| __| / /
 | | (_| | |_) | |_| \__ \ |_ / /
  \ \__,_|_.__/ \__,_|___/\__/_/                __ _
   \____/__| (_)_ __ | |_       ___ ___  _ __  / _(_) __ _
  / _ \/ __| | | '_ \| __|____ / __/ _ \| '_ \| |_| |/ _` |
 |  __/\__ \ | | | | | ||_____| (_| (_) | | | |  _| | (_| |
  \___||___/_|_|_| |_|\__|     \___\___/|_| |_|_| |_|\__, |
                                                     |___/
```

## Overview

[ESLint](https://eslint.org) rules for my personal projects.

## Installation

This module should be installed as one of your project's `devDependencies`:

```
npm install --save-dev @bust/eslint-config
```

## Usage

Add an extends rule to your `.eslintrc`:

```javascript
{
    "extends": "@bust/eslint-config",
    "rules": {
        // overrides
    }
}
```
