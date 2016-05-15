---
layout: doc
title: Ubuntu Template
permalink: /doc/templates/ubuntu/
redirect_from:
- /en/doc/templates/ubuntu/
- /doc/Templates/Ubuntu/
- /wiki/Templates/Ubuntu/
---

Ubuntu template(s)
==================

If you like to use Ubuntu Linux distribution in your AppVMs, you can build and
install one of available Ubuntu templates. Those template currently are not
available in ready to use binary packages, because Canonical does not allow
to redistribute a modified Ubuntu. The redistribution is not allowed by their
[Intellectual property rights policy](http://www.ubuntu.com/legal/terms-and-policies/intellectual-property-policy).


Install
-------

It can built using [Qubes Builder](/doc/qubes-builder/). You can also access its
documentation in the [source code
repository](https://github.com/QubesOS/qubes-builder/blob/master/README.md).

To quickly prepare the builder configuration, you can use `setup` script
available in the repository - it will interactively ask you which templates you
want to build.

Known issues
------------

This Ubuntu template is not currently building (2016-05-15) with Qubes 3.1.  Ubuntu 14.04 LTS (Trusty) does not include systemd, which is required by the current Qubes builder and this template hasn't been updated to support either 14.10 (which does include systemd), or the current Ubuntu 16.04 LTS (Xenial). See [this thread](https://groups.google.com/forum/#!searchin/qubes-users/ubuntu$2016.04/qubes-users/w0uZNr8nno8/n1fe6dLtBQAJ).

If you want to help in improving the template, feel free to
[contribute](/wiki/ContributingHowto).
