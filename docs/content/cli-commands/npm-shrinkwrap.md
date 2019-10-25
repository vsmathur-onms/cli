---
section: cli-commands 
title: npm-shrinkwrap
description: Lock down dependency versions for publication
---

# npm-shrinkwrap

## Lock down dependency versions for publication

### Synopsis

```bash
npm shrinkwrap
```

### Description

This command repurposes `package-lock.json` into a publishable
`npm-shrinkwrap.json` or simply creates a new one. The file created and updated
by this command will then take precedence over any other existing or future
`package-lock.json` files. For a detailed explanation of the design and purpose
of package locks in npm, see [npm-package-locks](npm-package-locks).

### See Also

* [npm-install](/cli-commands/npm-install)
* [npm-run-script](/cli-commands/npm-run-script)
* [npm-scripts](/using-npm/scripts)
* [package.js](/configuring-npm/package.json)
* [npm-package-locks](/configuring-npm/package-locks)
* [package-lock.json](/configuring-npm/package-lock.json)
* [npm-shrinkwrap.json](/configuring-npm/shrinkwrap.json)
* [npm-ls](/cli-commands/npm-ls)