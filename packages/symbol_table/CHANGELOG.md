# Change Log

## 5.3.0

* Require Dart >= 3.5
* Updated `lints` to 5.0.0

## 5.2.0

* Require Dart >= 3.3
* Updated `lints` to 4.0.0

## 5.1.0

* Updated `lints` to 3.0.0
* Fixed lints warnings

## 5.0.0

* Require Dart >= 3.0

## 5.0.0-beta.1

* Require Dart >= 3.0

## 4.0.0

* Require Dart >= 2.17

## 3.0.1

* Fixed license link

## 3.0.0

* Upgraded from `pendantic` to `lints` linter
* Published as `belatuk_symbol_table` package
* Fixed linter warnings

## 2.0.2

* Resolved static analysis warnings

## 2.0.1

* Resolved static analysis warnings

## 2.0.0

* Migrated to work with Dart SDK 2.12.x NNBD

## 1.0.4

* Added `context` to `SymbolTable`.

## 1.0.3

* Converted `Visibility` into a `Comparable` class.
* Renamed `add` -> `create`,  `put` -> `assign`, and `allVariablesOfVisibility` -> `allVariablesWithVisibility`.
* Added tests for `Visibility` comparing, and `depth`.
* Added `uniqueName()` to `SymbolTable`.
* Fixed a typo in `remove` that would have prevented it from working correctly.

## 1.0.2

* Added `depth` to `SymbolTable`.
* Added `symbolTable` to `Variable`.
* Deprecated the redundant `Constant` class.
* Deprecated `Variable.markAsPrivate()`.
* Added the `Visibility` enumerator.
* Added the field `visibility` to `Variable`.
