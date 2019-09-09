# bsi-data-model-map

The diagram in this repository attempts to show the many data models, serialization formats, and mappings currently in use within the BuildingSmart Interational and ISO/STEP communities. Model formats are colored by owning entity. Mappings between formats are given unique IDs (prefixed with "E"). Known tooling that supports each mapping are provided below.

This diagram is surely incorrect and incomplete. Additions and corrections welcome!

## Mapping Implementations

* E1:
  - EuroStep eep parser (deprecated; limited reference support)
  - [ExpressEngine](https://sourceforge.net/projects/exp-engine/)

* E2:
  - STEP's [reeper](https://sourceforge.net/p/reeper)

* E3:
  - via [Eclipse EMF](https://www.eclipse.org/modeling/emf/)
  
* E4:
  - via [Eclipse EMF](https://www.eclipse.org/modeling/emf/)

* E5:
  - STEP's [reeper](https://sourceforge.net/p/reeper)

* E6 and E7 and E8:
  - [IfcDoc](https://technical.buildingsmart.org/resources/ifcdoc/)

* E9:
  - XSL Transforms from Enterprise Architect within IFC-Rail Group

* E10
  - [IFCConvert](http://ifcopenshell.org/ifcconvert.html)

* E11:
  - Custom processing within IFC-Rail Group

* E12:
  - OMG ODM [Informative Mapping](https://www.omg.org/spec/ODM/1.1/PDF)
  
* E13:
  - OMG ODM [Informative Mapping](https://www.omg.org/spec/ODM/1.1/PDF) (some restrictions)

# License
All work within this repository is available under the MIT License.
