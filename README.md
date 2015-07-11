# textexpander-mac-keys

[![Semantic Versioning](https://img.shields.io/github/release/davidwaterston/textexpander-mac-keys.svg)](http://semver.org/)
[![MIT Licence](http://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/davidwaterston/textexpander-mac-keys/blob/master/LICENSE)
[![Releases signed with Gnu Privacy Guard](https://img.shields.io/badge/gpg-signed-green.svg)](#verifying-releases)


A small group of [TextExpander](https://smilesoftware.com/TextExpander/index.html) snippets that can be used to insert Apple Mac symbols into a document.

![textexpander-mac-keys in action](https://raw.githubusercontent.com/wiki/davidwaterston/textexpander-mac-keys/images/keys3.gif)

Nineteen symbols are supported (⌥ appears twice as both ;alt and ;opt):

| Symbol | Key  | Shortcut |
|---|---|---|
| Alt | ⌥ | ;alt |
| Apple |  | ;apple |
| Backspace | ⌫ | ;backspace |
| Caps Lock | ⇪ | ;caps |
| Command | ⌘ | ;cmd |
| Control | ⌃ | ;ctrl |
| Delete | ⌦ | ;del |
| Down Arrow | ↓ | ;down |
| Eject | ⏏ | ;eject |
| Enter | ⌅ | ;enter |
| Escape | ⎋ | ;esc |
| Left Arrow | ← | ;left |
| Option | ⌥ | ;opt |
| Return | ↩ | ;return |
| Right Arrow | → | ;right |
| Shift | ⇧ | ;shift |
| Space | ␣ | ;space |
| Tab | ⇥ | ;tab |
| Up Arrow | ↑ | ;up |



## Installation

To install these snippets:

- Open TextExpander
- Click the + sign in the bottom left of the dialog and select _Add Group from URL..._ (or press ⌘ - L)
- Paste in the following URL: https://raw.githubusercontent.com/davidwaterston/textexpander-mac-keys/master/mac-keys.textexpander
- Press _OK_

After a few seconds a new group named _Mac Keys_ will appear; your new snippets are ready to use!


## Compatibility
These snippets have been tested and confirmed to work with TextExpander version 5.01 and later, though they should also work with earlier versions without problem.


## Release History
See the [change log](https://github.com/davidwaterston/textexpander-mac-keys/blob/master/CHANGELOG.md) file for more details.


## Verifying Releases
I use <a href="http://semver.org" target="_blank" alt="Semantic Versioning">Semantic Versioning</a> to number releases. Each release is tagged with the appropriate version number and signed using <a href="https://www.gnupg.org" target="_blank" alt="Gnu Privacy Guard (GPG)">Gnu Privacy Guard (GPG)</a>. The public key used to sign releases is
```
Name: David Waterston
Email: david@davidwaterston.com
Key ID: A7AD9C85
Signature: 71A9 DC13 447A 1E4F C6EB  5D64 DE08 A991 A7AD 9C85
```
This public key is included in the repository with a SHA1 of 16d013451476fa4a1a67d6ad4b90583e205b53b1.
After cloning the repo, and assuming you have GPG installed correctly, you can import this key into your keychain
```
git cat-file blob pubkey | gpg --import
```
When this public key is successfully imported, you can use it to verify the integrity of any of the tagged releases of this repo
```
git tag -v v1.0.0
```
which should produce output similar to:
```
object 04f37a55784c1f3abc2cf927a935a488aa954035
type commit
tag v1.0.0
tagger David Waterston <david@davidwaterston.com> 1427387056 +0000

Initial commit

This is just an example so don't get fixated on the details, what matters is the signature!
gpg: Signature made Thu 26 Mar 16:24:16 2015 GMT using RSA key ID A7AD9C85
gpg: Good signature from "David Waterston <david@davidwaterston.com>" [ultimate]
```
The important thing to notice here is that the RSA key ID matches mine (A7AD9C85) and the line that says that this is a good signature.

The public key can further be verified by checking the details held on <a href="http://pgp.mit.edu/pks/lookup?search=david%40davidwaterston.com&op=index&fingerprint=on&exact=on" target="_blank" alt="pgp.mit.edu">pgp.mit.edu</a>.


## License
Copyright (c) 2015 David Waterston. All rights reserved.
Distributed under an MIT license. See the [LICENSE](https://github.com/davidwaterston/textexpander-mac-keys/blob/master/LICENSE) file for more details.
