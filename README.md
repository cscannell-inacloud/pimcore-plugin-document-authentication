Doucment Authentication Plugin
================================================

Developer info: [Pimcore at basilicom](http://basilicom.de/en/pimcore)

## Synopsis

This Pimcore <http://www.pimcore.org> plugin adds a
front controller plugin to enable selective HTTP Basic Authentication
on a per-document basis via document properties.

## Code Example / Method of Operation

Just enable the plugin, adapt the website properties (username and password)
in the website settings and add the predefined property to a document in
the document tree.

## Motivation

An existing website might be extended with new document pages which
should be inaccessible to ordinary users for preview. The built-in
HTTP Basic Authentication feature of Pimcore is global. This
plugin enables password protection on a document level.

## Installation

Add "basilicom-pimcore-plugin/document-authentication" as a requirement to the
composer.json in the toplevel directory of your Pimcore installation.

Example:

    {
        "require": {
            "basilicom-pimcore-plugin/document-authentication": ">=1.0.0"
        }
    }

## API Reference

* n/a

## Tests

* none

## Contributors

* Conrad Guelzow <conrad.guelzow@basilicom.de>

## License

* BSD-3-Clause
