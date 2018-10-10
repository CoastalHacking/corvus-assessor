# Corvus Assessor

Corvus Assessor is an [Oomph][0]-configure, customized Eclipse IDE useful for security-centric application code reviews.

## Install

Note: pasting may require right-clicking and selecting `Paste` instead of a key sequence

* Download and run the [Eclipse Installer][1]
* On the Product page:
  * Select `<User Products>`;
  * Click the green plus symbol on the upper right;
  * Paste copy [tnhis raw URL][7], which points to [corvus.assessor.product.setup](/oomph/corvus.assessor.product.setup).
* On the Projects page:
  * Collapse `Eclipse Projects`;
  * Expand `GitHub Projects`;
  * Click the green plus symbol on the upper right;
  * Paste in this [this raw URL][8]  which points to [corvus.assessor.project.setup](/oomph/corvus.assessor.project.setup).

## corvus.assessor.product.setup

Contains features and plugins useful for security-centric Java code reviews.
 
* [Web tools platform][3]
* [Java EE tools][4]
* [EGit][5]
* [JavaScript Developer tools][6]

And others...

## corvus.assessor.project.setup

Pre-configured projects:

* Burp with launcher
* Java servlet container

## Develop

Oomph tutorial [here][2].

[0]: https://projects.eclipse.org/projects/tools.oomph
[1]: https://wiki.eclipse.org/Eclipse_Installer
[2]: https://eclipsesource.com/blogs/tutorials/oomph-basic-tutorial/
[3]: https://www.eclipse.org/webtools/
[4]: https://www.eclipse.org/webtools/jee/
[5]: https://www.eclipse.org/egit/
[6]: https://www.eclipse.org/webtools/jsdt/
[7]: https://raw.githubusercontent.com/CoastalHacking/corvus-assessor/master/oomph/corvus.assessor.product.setup
[8]: https://raw.githubusercontent.com/CoastalHacking/corvus-assessor/master/oomph/corvus.assessor.project.setup