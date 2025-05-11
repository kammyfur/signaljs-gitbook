# Lifecycle

Signal.js versions lifecycle follows a basic strategy:

* The 2 latest minor (x.**x**) and 2 latest major (**x**.x) versions are supported
* New features introduced in later versions are not backported, only bug fixes and security patches
* Development versions (tagged `dev`) go out of support as soon as a newer version is released, no quality assurance or guarantee is provided for these versions
* Versions starting with 0.x.x are never guaranteed to be stable and may contain breaking changes between minor versions
* New features are introduced in major (**x**.x) versions, minor versions (x.**x**) may introduce non-breaking changes to existing features, and patch versions (x.x.**x**) only fix bugs and/or security issues

If you have, for example, the following list of versions:

* 2.1.0
* 2.0.1
* 2.0.0
* 1.3.2
* 1.3.1
* 1.3.0
* 1.2.2
* 1.2.1

Only versions 2.1.0, 2.0.1 and 1.3.2 are supported.
