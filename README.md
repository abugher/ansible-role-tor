# BUGS

This role must be redeployed after an OS major version upgrade.  The tor package will be upgraded by the OS from the old backports release to the current non-backports release.  The Tor network will then deprioritize selection of this relay due to old software.  I do not think there is a way to specify to Debian that a package should always come from the backports release associated with the current OS release.
