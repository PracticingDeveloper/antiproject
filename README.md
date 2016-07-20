# Antiproject Rules

* Don't do anything dangerous
* Don't do anything mean
* Always use `bin/inject` to add features, don't check in source.
* Always use `bin/exec` to run features.
* You may modify both `bin/inject` and `bin/exec`, but if you break old behavior,
your changes will be reverted.
* Project is not limited to Ruby. But don't break ability to use RUby.
* Rewriting someone else's commands is OK. But don't be surprised if they
revert your commit or rewrite it again. And don't get into revert wars...
unless they are hilarious.
* No documentation allowed, unless it's directly implemented inside of `proj.dat`,
or included in a commit message.
* Dependencies on third party systems and services are fine, so long as they
don't break existing functionality and are entirely optional.

**Patches accepted from members of The Workshop only for now**

## Getting started

```
$ bundle
$ ./bin/exec hello
``