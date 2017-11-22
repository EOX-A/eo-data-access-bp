![OGC Logo](http://portal.opengeospatial.org/files/?artifact_id=11976&format=gif "OGC Logo")

# OGC® EO Data Access Best Practice

This OGC Best Practice document details proposed configuration and
instantiation conventions for access to Earth Observation (EO) data developed
in the European Space Agency (ESA) funded project Evolution of EO Online Data
Access Services (EVO-ODAS).

It defines how to utilize WCS with EO products including generic conventions
and recommendations for data and metadata mapping and conversion which are to
be used in concrete tailoring for specific missions. It further considers how
to link to other services like CSW, WMS, and WPS.

## About

This GitHub repository tracks the latest version of the Best Practice document
as it evolves. Pull requests for fixes or new functionality are appreciated.
The document is done in [asciidoc](http://www.methods.co.nz/asciidoc/) a format
supported by GitHub, similar to markdown but with some additional features.

## Contributing

The contributor understands that any contributions, if accepted by the OGC
Membership, shall be incorporated into the formal Best Practice document and
that all copyright and intellectual property shall be vested to the OGC.

The WCS Standards Working Group (SWG) is the group at OGC responsible for the
stewardship of the document.

The WCS SWG currently has the following email list:
   - wcs.swg@lists.opengeospatial.org -- [sign up here](https://lists.opengeospatial.org/mailman/listinfo/wcs.swg)
      - Private List
      - Access controlled archives
      - Requires OGC membership and Observer Agreement to protect IPR (intellectual property rights)

**SWG Chair: Peter Baumann**

**SWG Vice Chair: Stephan Meißl**

## Editing and commenting

The WCS SWG is accepting public comments and suggested revisions to the
document via GitHub. To suggest changes to the standard please fork the
repository and submit a pull request with the desired changes. Please make one
pull request per logical requested change and be sure to include a comment in
the PR with any justification or reasoning on why the change is needed.

For more general comments (that don't include actual text changes to the
specification) please create a GitHub issue for that topic.

Complex changes and feature requests must go through the [change
request](http://portal.opengeospatial.org/public_ogc/change_request.php)
process. The details entered in the change request form will help the SWG
adjudicate and prioritize the request.

## Building

To produce the HTML of this document run `asciidoctor --safe -a data-uri -o
standard_document.html standard_document.adoc`.

To produce the PDF of this document run `bundle exec asciidoctor-pdf --safe -o
standard_document.pdf standard_document.adoc`

Before the first time also install dependencies via `bundle install`.

The `gh-pages` branch holds the latest approved version of the build and is
viewable at https://eox-a.github.io/eo-data-access-bp/.
