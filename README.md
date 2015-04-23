![OGC Logo](http://portal.opengeospatial.org/files/?artifact_id=11976&format=gif "OGC Logo")

Document Template
==========

To create your own repository using this repository as a template, do the following:
   * Create the new repository (e.g., `my-repo`) as per https://help.github.com/articles/creating-a-new-repository
   * Clone the template repository and mirror it into the new repository:
```
git clone https://github.com/opengeospatial/document-template.git
cd document-template
git push --mirror https://github.com/youruserid/my-repo.git
```

For more information, see https://help.github.com/articles/duplicating-a-repository/.

About
-----

This GitHub repository is designed to be used as a basis for official OGC documents.
It is based on the [GeoPackage specification](http://www.geopackage.org/spec). 
With this repository the OGC invites collaboration and comments directed at the development 
and enhancement of this candidate standard. 

The repo tracks the latest version of the specification as it evolves. Pull requests for fixes are
appreciated, and new functionality will still be considered even though version 1.0 has been adopted. The spec
is done in [asciidoc](http://www.methods.co.nz/asciidoc/) a format supported by GitHub, similar to markdown
but with some features that make it better for specifications, like automatic section numbering.

Contributing
------------
The contributor understands that any contributions, if accepted by the OGC Membership, shall 
be incorporated into the formal OGC GeoPackage standards document and that all copyright and 
intellectual property shall be vested to the OGC.

_describe the working group responsible for the stewardship of this document_


Editing and commenting
----------------------
OGC is accepting public comments and suggested revisions to the specification via GitHub. 
To suggest changes to the specification please fork the repository and submit a pull request with
the desired changes. Please make one pull request per logical requested change and be sure to
include a comment in the PR with any justification or reasoning on why the change is needed.

For more general comments (that don't include actual text changes to the spec) please create a GitHub [issue](https://github.com/opengeospatial/document-template/issues) for that topic.

Complex changes and feature requests must go through the [change request](http://portal.opengeospatial.org/public_ogc/change_request.php) process. The details entered in the change request form will help OGC adjudicate and prioritize the request.

For more detailed guidance, or if you are new to GitHub, see the [Process page](process.md) for additional 
information on editing.
