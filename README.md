# lockbox's gdbmi

Forked repo thats expanding to a more general use case as the old repo focused exclusively on source-based rust stuff under rr.

## TODO
working on getting the following upstreamed into this repo
- [x] remove some integer overflow panics
- [x] don't oom on empty stdout/stdin buffers
- [x] breakpoints support having negative id's (hidden breakpoint)
- [x] support address based breakpoint insertion
- [ ] rework event loop
- [ ] more e2e testing
- [ ] typing for reading / writing memory
- [ ] typing for reading / writing to registers
- [ ] typing for watchpoints
- [ ] extend typing for breakpoints
- [ ] add a blocking api


## Old readme contents

[![Crates.io](https://img.shields.io/crates/v/gdbmi)](https://crates.io/crates/gdbmi)
![MIT Licensed](https://img.shields.io/crates/l/gdbmi)

Interact with a GDB session through the GDB machine interface

The parser is ported from pygdbmi, written by Chad Smith, which
[is also MIT licensed][pygdbmi-license].

[pygdbmi-license]: https://github.com/cs01/pygdbmi/blob/master/LICENSE
