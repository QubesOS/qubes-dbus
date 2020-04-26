**This component is obsolete, functionally replaced with https://github.com/QubesOS/qubes-core-admin-client**

# Qubesdbus

This package contains a qubes extension called `QubesDbusProxy` and Qubes D-Bus
services. UI developer should use the D-Bus API to interact with
`qubes-core-admin`.

## Services

* `org.qubes.DomainManager1` - equivalent to `qubes.Qubes` for managing domains.
* `org.qubes.Labels1`   - Collection holding all the labels provided by the
  system

## Objects

* `Domain` is managed by `DomainManager1` and represents a domain. Its D-Bus
object path is `/org/qubes/DomainManager1/domains/QID`
* `Label` a qubes label. Its D-Bus object path is `org/qubes/Labels1/labels/COLORNAME`
