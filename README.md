<h1><img src="https://github.com/OpenTNF/opentnf/blob/master/logo.png" tag="OpenTNF" style="float: left"> OpenTNF</h1>

OpenTNF's mission statement:

_Create and maintain, as a community, an international, open and efficient solution for exchange of Transport Network data. The solution will enable easier usage of data on multiple platforms._

The OpenTNF™ format is specified as a set of data tables that in principal may be implemented in any relational database engine. An OpenTNF™ dataset is compliant with INSPIRE DS TN and may contain the following types of data:

* Transport network including the definition of linear referencing, geometric, topological and temporal aspects
* Attribution and features, here called transport properties, related to the geography and/or transport network using linear referencing mechanisms. OpenTNF™ uses a generic approach where all types use the same schema where the types are defined in a separate catalogue data structure.
* A transport property type catalogue defining the various transport property types. This catalogue may also contain definitions of secondary linear referencing systems.
* Metadata, also according to any XML compliant standard such as ISO 19139
* Update (transaction) information for the case that the dataset represents a set of updates

To align to this specification an implementation shall implement all mandatory and conditional elements as specified. Optional elements may be implemented and if they are implemented they shall be implemented as specified. Finally, an implementation may add additional elements and extend this specification provided that all mandatory, conditional and optional elements are not affected. This means that implementations are free to add tables or columns.

The first release of the specification is available for download <a href="https://github.com/OpenTNF/opentnf/releases/download/1.0/OpenTNF.-.white.paper.1.0.pdf" target="_blank">OpenTNF 1.0  <img src="https://github.com/OpenTNF/opentnf/blob/master/pdf_icon.png" tag="pdf"></a>

While OpenTNF™ initially was developed by Triona AB, everyone is invited to contribute to its further development and maintenance. We encourage you to use, read, review, evaluate, discuss and comment this document and OpenTNF™.

The OpenTNF™ specification is licensed under the Creative Commons Attribution-No Derivative Works 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nd/4.0/.
