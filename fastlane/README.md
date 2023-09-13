fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios register_app

```sh
[bundle exec] fastlane ios register_app
```

Register new app in App Store Connect

### ios sandbox

```sh
[bundle exec] fastlane ios sandbox
```

Sigh all development certificates

### ios get_dev_certs

```sh
[bundle exec] fastlane ios get_dev_certs
```



### ios sync_device_info

```sh
[bundle exec] fastlane ios sync_device_info
```



### ios sync_signing_assets

```sh
[bundle exec] fastlane ios sync_signing_assets
```

Sync team Code-Signing assets

### ios build_appstore

```sh
[bundle exec] fastlane ios build_appstore
```

Build for App Store submission

### ios build_adhoc

```sh
[bundle exec] fastlane ios build_adhoc
```

Build for Ad hoc submission

### ios distribute_to_appstore

```sh
[bundle exec] fastlane ios distribute_to_appstore
```



### ios release

```sh
[bundle exec] fastlane ios release
```



### ios gitCheck

```sh
[bundle exec] fastlane ios gitCheck
```



### ios unitTest

```sh
[bundle exec] fastlane ios unitTest
```



### ios lint

```sh
[bundle exec] fastlane ios lint
```



----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
