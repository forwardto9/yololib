yololib
=======

dylib injector for mach-o binaries


Usage
============

Self-explainatory

`yololib` `binary` `dylib file`

Ex:

```
/usr/bin/codesign --force --sign "$EXPANDED_CODE_SIGN_IDENTITY" "$BUILT_PRODUCTS_DIR/$TARGET_NAME.app/Frameworks/LibInjectFramework"
yololib "$BUILT_PRODUCTS_DIR/$TARGET_NAME.app/$TARGET_NAME" "Frameworks/LibInjectFramework"
```
