# EXSLT Redux

EXSLT resurrected for Umbraco 7.x


### Background

With the release of Umbraco 7, the previously built-in EXSLT extension methods have been removed.  The reason for this is [explained on ticket #U4-2742](http://issues.umbraco.org/issue/U4-2742#comment=67-9450). (*In a nutshell the many of the EXSLT extension methods haven't worked since Umbraco 4.5 / .NET 4.0.*)

However since there are still other EXSLT extension methods that work, there has been a demand for continued support. Thus this package was created.


### Installation

This package is one of those "install and forget" packages, as in there is no configuration or set-up required.

To install the Umbraco package, here are the steps:

1. Login to your Umbraco back-office.
2. Go to the *Developer* section.
3. From the tree, expand the *Packages* folder.
4. Select *Install local package*.
5. Follow the on-screen instructions.


### References

* [U4-2742 Remove legacy xsltExtensions.config - xslt extensions are configured using attributes](http://issues.umbraco.org/issue/U4-2742)
* [EXSLT library - does anyone use it?](https://groups.google.com/forum/#!msg/umbraco-dev/1-lhkqfe3xs/rrbZCknMAlAJ)
* [U4-2836 Remove EXSLT xslt extensions since many have been broken for some time](http://issues.umbraco.org/issue/U4-2836)
