*So safe, so clean!*


# Design Guidelines

We strictly observe and enforce the most glorious design patterns of Foote and Yoder.

(from http://www.laputan.org/mud/mud.html#BigBallOfMud)

**BIG BALL OF MUD**

- You need to deliver quality software on time, and under budget.
- *Therefore*, focus first on features and functionality, then focus on architecture and performance.

**THROWAWAY CODE**

- You need an immediate fix for a small problem, or a quick prototype or proof of concept.
- *Therefore*, produce, by any means available, simple, expedient, disposable code that adequately addresses just the problem at-hand.

**PIECEMEAL GROWTH**

- Master plans are often rigid, misguided and out of date. Users’ needs change with time.
- *Therefore*, incrementally address forces that encourage change and growth. Allow opportunities for growth to be exploited locally, as they occur. Refactor unrelentingly.

**KEEP IT WORKING**

- Maintenance needs have accumulated, but an overhaul is unwise, since you might break the system.
- *Therefore*, do what it takes to maintain the software and keep it going. Keep it working.

**SHEARING LAYERS**

- Different artifacts change at different rates.
- *Therefore*, factor your system so that artifacts that change at similar rates are together.

**SWEEPING IT UNDER THE RUG**

- Overgrown, tangled, haphazard spaghetti code is hard to comprehend, repair, or extend, and tends to grow even worse if it is not somehow brought under control.

- *Therefore*, if you can’t easily make a mess go away, at least cordon it off. This restricts the disorder to a fixed area, keeps it out of sight, and can set the stage for additional refactoring

**RECONSTRUCTION**

- Your code has declined to the point where it is beyond repair, or even comprehension.
- *Therefore*, throw it away and start over.

# Collaboration Rules

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
$ ./ap
```

(also try `./ap/repl`... it's handy!)

## License

This project is licensed under the CC0 1.0 Universal License
(essentially public domain)

See LICENSE.md for details.
