# Tagging4Tracking

A proposal on how to manage comments in Red Hat technical reviews.

## Build

If you need to build this document, you must install:

* Docbook
* xmlto
* fop

To build to plain text:

    $ xmlto txt tagging4tracking.xml

To build to HTML or plain text:

    $ xmlto html-nochunks tagging4tracking.html

To build to pdf:

    $ xmlto fo tagging4tracking.xml
    $ fop tagging4tracking.xml tagging4tracking.pdf

## License

This is licensed under the GNU Free Documentation 1.3 license. See ``LICENSE`` file for details.

## Bugs

In order of preference:

1. Comment in the XML file
1. File a Github issue

