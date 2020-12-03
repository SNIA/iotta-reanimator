# IOTTA Re-Animator Index

This repository serves as an index to other Github repositories that
comprise the Re-Animator tracing and replay tool.  This index
repository contains no code, only links to other repositories that are
part of Re-Animator.

For more information on the Re-Animator project, please see our paper
[Re-Animator: Versatile High-Fidelity Storage-System Tracing and Replaying](https://doi.org/10.1145/3383669.3398276).

* [Re-Animator LTTNG](http://github.com/SNIA/reanimator-lttng) is
  the repository you should clone if you want to use the LTTNG-based
  implementation of Re-Animator.  This version imposes a low overhead
  on the traced program, but requires that you install kernel patches
  to use it.

* [Re-Animator Strace](http://github.com/SNIA/reanimator-strace) is the
  repository you should clone if you want to use the strace-based
  implementation of Re-Animator.  This version has higher overhead but
  requires no kernel changes or special privileges.

The following repositories are needed by Re-Animator, but will be
automatically cloned by the install scripts in the above two
repositories, so there is normally no need to clone them separately.

* [Re-Animator LTTNG UST](http://github.com/SNIA/reanimator-lttng-ust)
  contains user-space tools for Re-Animator LTTNG.  It will
  automatically be cloned by the install scripts in LTTNG Tools,
  above.

* [Re-Animator LTTNG Tools](http://github.com/SNIA/reanimator-lttng-tools)
  contains the command-line tool that invokes LTTNG.  It will
  automatically be cloned by the install scripts in LTTNG Tools,
  above.

* [Re-Animator Babeltrace](http://github.com/SNIA/reanimator-babeltrace)
  contains our version of the babeltrace tool, which is needed by
  Re-Animator.  It will automatically be cloned by the install scripts
  in LTTNG Tools, above.

* [Re-Animator LTTNG Modules](http://github.com/SNIA/reanimator-lttng-modules)
  contains the kernel modules needed by Re-Animator LTTNG.  It will
  automatically be cloned by the install scripts in LTTNG Tools,
  above.
* [Re-Animator Userspace RCU](http://github.com/SNIA/reanimator-userspace-rcu )
  contains the user-space read-copy-update update library used by
  Re-Animator LTTNG.  It will automatically be cloned by the install
  scripts in Re-Animator LTTNG Tools.

* [Re-Animator Library](http://github.com/SNIA/reanimator-library)
  contains the libraries needed by Re-Animator.  It will automatically
  be cloned by the install scripts in Re-Animator LTTNG Tools or
  Re-Animator Strace, above.

Persons who wish to contribute to any of the IOTTA repositories should
either be a member of the IOTTA TWG, or should complete the simple
[SNIA Contributor License](https://www.snia.org/CLA).
