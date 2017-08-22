# Besana Firefox and Chrome Add-ons
This is an extension for using Besana (https://besana.amebis.si) in Firefox and Chrome. It's a fork from [LanguageTool for Firefox and Chrome](https://github.com/languagetool-org/languagetool-browser-addon).

## Main changes to the source code
* All the language selection options and settings were removed, only supported language is Slovenian.
* Personal dictionary was removed.
* Default server url was changed to a http://localhost:225/api/v2, which is a default url on which Besana listens.
* "Checked by" message is always visible.
* Localization string were changed to reflect product name.
* Option (link) to rate/review extension was removed.
* Privacy policy was removed.
* Page tracking was removed
* Privacy notes were removed.
* Url of a page which is opened after the extension is uninstall was changed.
* Link and message for Google Docs extension was removed.

All the changes are also described in commit messages.

## License
Lesser General Public License 2.1 or later, see file [COPYING](COPYING).