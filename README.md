# iSAQB Glossary of Software Architecture Terminology

A comprehensive glossary of software architecture terminology,
many of them used in the iSAQB foundation and advanced level curricula.

![](./glossary-cover-small.jpg)

This repository contains the sources for the published version of
the iSAQB glossary, available both online and in various eBook formats
at [Leanpub (https://leanpub.com/isaqbglossary)](https://leanpub.com/isaqbglossary).

We also keep our reference translations, currently between English <-> German,
these are generated from a JSON document into the markdown book source. You can
generate these translations by calling `./gradlew run` (on unix or osx)
or `.\gradlew.bat run` from the command line in directory `translator`.



## Suggestions Welcome

We welcome suggestions and critique of any kind: Just
[open an issue](https://github.com/isaqb-org/glossary/issues)
here on Github!

## Book Generation (aka "build")

This repository is linked with Leanpub over a webhook: Every commit in `master` triggers
a preview-build at Leanpub. The results (in pdf, mobi and epub formats) are stored in
a Dropbox folder. Authors and contributors are given access to this Dropbox.


## Contributors

The initial version of this glossary has been contributed by [Gernot Starke](http://gernotstarke.de).
Prior versions of an (German) glossary had been compiled and edited by Dr. Ulrich Becker,
Phillip Ghadir and others.


Currently the contens are maintained by volunteers from the [iSAQB e.V.](http://isaqb.org),
a non-profit volunteer association - most of them are mentioned the contributors list of this repository.

#### How to Become Contributor

You can become contributor (and will be added to the Leanpub contributor page) if
you:

1. Fix 3 or more issues from the Github issue list
2. Open 5 significant issues (typos, spelling mistakes, simple formating issues and
  other trivial stuff does not qualify as _significanct_).
3. Provide significant input by mail or other means to existing authors.
Statements of the form "xy should be done, but I won't do it.." without further
contributions do not qualify as _significant_.  

#### How to Become an Author

You will be promoted to the Leanpub author list of the book if you either:

1. Provide 3 or more new definitions of terms that will be accepted by the
existing authors.
2. Substantially enhance 5 or more definitions that will be accepted by the
existing authors. Examples: Include diagrams to illustrate patterns or concepts.
3. Substantially enhance other aspects of the glossary that will be accepted by the
existing authors.
4. Crosscheck one (complete) CPSA-Advanced Level module for terms missing in
the glossary.
(You might need a (free) Leanpub account to become an author)

## Legal

This book is licensed under a
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


![](./cc-by.png)

The following is only a brief summary and no substitution for the real
[licence](https://creativecommons.org/licenses/by/4.0/).


The cc-4.0-by license means that you might:

* Share — copy and redistribute the material in any medium or format
* Adapt — remix, transform, and build upon the material for any purpose, even commercially.
* The licensor cannot revoke these freedoms as long as you follow the license terms.

You must:

* Give **appropriate credit**,
* Provide a link to the license (https://creativecommons.org/licenses/by/4.0/), and
* Indicate if changes were made.
