# Antiproject Rules

* Don't do anything dangerous
* Don't do anything mean
* Assume `proj.dat` can be corrupted at any time, keep backups
* Always use `bin/exec` to run features.
* Always use `inject` command to add features, don't check in source.
* Use the `merge` command to resolve store conflicts
* You may modify `bin/exec`, but if you break old behavior,
your changes will be reverted.
* Project is not limited to Ruby. But don't break ability to use RUby.
* Rewriting someone else's commands is OK. But don't be surprised if they
revert your commit or rewrite it again. And don't get into revert wars...
unless they are hilarious.
* No documentation allowed, unless it's directly implemented inside of `proj.dat`,
or included in a commit message.
* Dependencies on third party systems and services are fine, so long as they
don't break existing functionality and are entirely optional.
* Need help? Ask in #antiproject

**Patches accepted from members of The Workshop only for now. But if you are a Workshop member, just ask and I'll add you to the project as a committer.**

## Getting started

```
$ bundle
$ ./bin/exec hello
```

## License

This project is licensed under the CC0 1.0 Universal License
(essentially public domain)

See LICENSE.md for details.
