# Template IEPD
This is a template IEPD for NIEM 4.1. It is designed to be a starting point for 
IEPD creators. 

IEPDs built from this template should follow the NIEM-MPD 4.1 specification 
located here:
https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html

The NIEM-MPD specification defines the contents and structure of IEPDs including 
metadata, XML Schema documents, and documentation.

[![Build Status](https://travis-ci.org/NIEM/Template-IEPD.svg?branch=master)](https://travis-ci.org/NIEM/Template-IEPD)

## This template IEPD contains
1. NIEM schema subset
  https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_4.2

  See the NIEM Schema Subset Generation Tool (SSGT) to create a subset for 
  the IEPD based on requirements: http://tools.niem.gov/niemtools/

2. NIEM extension schema
  https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_4.3

  An extension schema contains a conformance target identifier as follows:
  ct:conformanceTargets="http://reference.niem.gov/niem/specification/naming-and-design-rules/4.0/#ExtensionSchemaDocument"

3. Catalog file
  https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.1

4. README
  https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.4

5. Change Log
  https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.3

6. Conformance Assertion
  https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.7
