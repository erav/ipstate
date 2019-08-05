# ipstate

A declarative ip API for hosts.

## What is it?
Ipstate is a library that manages host networking settings in a declarative
manner using the [pyroute2](https://pypi.org/project/pyroute2/ "pyroute2")
library.

The networking state is described by a pre-defined schema.
Reporting of current state and changes to it (desired state) both conform to
the schema.

Ipstate is aimed to be a provider for
[nmstate](https://github.com/nmstate/nmstate "nmstate").

