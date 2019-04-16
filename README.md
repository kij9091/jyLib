# jyLib

[![CI Status](https://img.shields.io/travis/Jiyoung Kim/jyLib.svg?style=flat)](https://travis-ci.org/Jiyoung Kim/jyLib)
[![Version](https://img.shields.io/cocoapods/v/jyLib.svg?style=flat)](https://cocoapods.org/pods/jyLib)
[![License](https://img.shields.io/cocoapods/l/jyLib.svg?style=flat)](https://cocoapods.org/pods/jyLib)
[![Platform](https://img.shields.io/cocoapods/p/jyLib.svg?style=flat)](https://cocoapods.org/pods/jyLib)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

jyLib is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'jyLib'
```

## Author

Jiyoung Kim, 9091kij@nexon.co.kr

## License

jyLib is available under the MIT license. See the LICENSE file for more info.
[!] Unknown command: `# jyLib`

Usage:

    $ pod trunk push [PATH]

      Publish the podspec at `PATH` to make it available to all users of the ‘master’
      spec-repo. If `PATH` is not provided, defaults to the current directory.

      Before pushing the podspec to cocoapods.org, this will perform a local lint of
      the podspec, including a build of the library. However, it remains *your*
      responsibility to ensure that the published podspec will actually work for your
      users. Thus it is recommended that you *first* try to use the podspec to
      integrate the library into your demo and/or real application.

      If this is the first time you publish a spec for this pod, you will
      automatically be registered as the ‘owner’ of this pod. (Note that ‘owner’ in
      this case implies a person that is allowed to publish new versions and add other
      ‘owners’, not necessarily the library author.)

Options:

    --allow-warnings           Allows push even if there are lint warnings
    --use-libraries            Linter uses static libraries to install the spec
    --use-modular-headers      Lint uses modular headers during installation
    --swift-version=VERSION    The SWIFT_VERSION that should be used to lint the spec.
                               This takes precedence over a .swift-version file.
    --skip-import-validation   Lint skips validating that the pod can be imported
    --skip-tests               Lint skips building and running tests during validation
    --silent                   Show nothing
    --verbose                  Show more debugging information
    --no-ansi                  Show output without ANSI codes
    --help                     Show help banner of specified command
# jyLib
