PIN Code Shapes
===============

India has 19,100 PIN codes served by ~155,000 post offices. This list is
available in the [All India Pincode Directory](https://data.gov.in/catalog/all-india-pincode-directory).

India Post mapped every post office in India. This is on
[Bhuvan's NSRC](http://bhuvan.nrsc.gov.in/governance/mcit_post) -- but the data
is not directly available.

Boundaries served by these post offices are not available. This repository is
an open tool that will

1. be seeded with polygons showing an estimated boundary for each post office
2. and allow India Post to edit the boundaries
3. as well as download the result in as a GeoJSON file that can be exported into other GIS software

Setup
-----

Upload the following keys on <https://postoffices.firebaseio.com/>:

- [points.json](https://postoffices.firebaseio.com/points.json): the post office
  locations as GeoJSON
- [base.json](https://postoffices.firebaseio.com/base.json): the village
  boundaries as GeoJSON
- [shapes.json](https://postoffices.firebaseio.com/shapes.json): the post office
  boundaries as GeoJSON

The edited post office boundaries can be downloaded from
[shapes.json](https://postoffices.firebaseio.com/shapes.json).

Contacts
--------

- John Wesley <wesley.neo@gmail.com>
- Nisha Thompson <nisha@datameet.org>
- Rajendra <rajendra@indiapost.gov.in>
- S Anand <s.anand@gramener.com>
- Srikanth Nadhumuni <srikanth@khoslalabs.com>
