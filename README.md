# XCFrameworks

Validate podspec:

```sh
pod lib lint dist/NAME.podspec

pod lib lint --skip-import-validation dist/NAME.podspec
```

Publish pod:

```sh
pod repo push https://github.com/ElfSundae/CocoaPods-Specs.git --use-json dist/NAME.podspec
```
