# Formal Concept Analysis

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

**Formal Context Schema © 2019 Jens Lorscheider**

A formal context can be represented by a cross table where rows are headed by object names and where columns are headed by attribute names. A cross in the table defines an object-attribute incidence relation. Usually, a formal context can be reduced to a simpler, less complex one by applying order-theoretic laws. From the viewpoint of lattice theory and the underlying algebraic structure with its closure operators, it is not possible to reconstruct the original formal context from the reduced context if no record of the reduction process has been kept. 

This project provides an XML schema file called `FormalContext.xsd` to resolve this issue by recording the reduction of a formal context. The formal context schema defines an XML structure of the reduction process, which is suitable for traceability. Traceability enables, for instance, the identification of support as fraction of specific objects for attribute implications in the reduced formal context with reference to the original context. Implications express relationships among formal context items and can be of high importance for the analysis of conceptual knowledge.

The XML schema definition language (XSD) is specified by the World Wide Web Consortium (W3C) at [XML Schema Part 1 (Structures)](https://www.w3.org/TR/xmlschema-1/) and [XML Schema Part 2 (DataTypes)](https://www.w3.org/TR/xmlschema-2/).

This project is licensed under the terms of the Creative Commons Attribution 4.0 International License https://creativecommons.org/licenses/by/4.0/, which permits unrestricted use, distribution, and reproduction in any medium, provided you give appropriate credit to the original author and the source, provide a link to the Creative Common license, and indicate if changes were made.

This project is still in progress, and it will take some time to finish the documentation, accompanying algorithms and unit tests.

## Approach inspired by

**Ganter, B., Wille, R.** (1999, 2024): Formal Concept Analysis, Mathematical Foundation, Second Edition.

**Ganter, B., Obiedkov, S.** (2016): Conceptual Exploration. 

**Qi, J., Wei, L., Wan, Q.** (2019): Multi-level granularity in formal concept analysis. Granular Computing 4, 351–362.
