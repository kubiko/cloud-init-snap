# cloud-init packaged as a snap

> cloud-init provides the standard for customising cloud instances

The repository contains the source to package cloud-init as a snap.
As cloud init cannot run fully confined, cloud init is invoked
through the hooks which are part of the base snap.
