# DGLux5 Localization

DGLux5 Translation Dictionaries

## Contributing

To contribute hand-made translations, follow the following process:

* Check if your locale exists.
  * If it doesn't exist then copy the "template.json" to "locales".
  * Rename to your lang (e.g. en_US.json), the file must end in *.json
* If it doesn't already exist, make a .json file with the same name in the "overrides" folder.
* Start translating! When you translate a value, put the key/value pair in the **overrides** folder, not locales.

## How DGLux generates translations

1. Looks for translation in "overrides/**(language)**.json", if it finds it use that
2. Looks for translation in "locales/**(language)**.json"
  * This will be auto-translated from Microsoft Cognative Services. Do **not** edit this file directly, it will be overwritten by our CI build.
