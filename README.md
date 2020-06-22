# CityGML_ADE_i-UR1.4

Data Encoding Specification of i-Urban Revitalization
- Urban Planning ADE –
ver.1.4

## Introduction
Urban planning has been contributing to the formation of healthy urban environments, preventing disorganized urban sprawl and encouraging infrastructure development in Japan. However, urban areas in Japan, which is facing depopulation and aging society, are at a big turning point. New social issues such as a rapid increase of empty apartments and lands, and non-universal design of facilities lie heavily on their sustainable development, especially regional area. Efficient urban management is required, and municipalities recognize the significance and importance of compact urban development from the perspective of administrative costs.

From this kind of circumstance, the Japanese government strongly promotes i) formation of a high-quality urban revitalization project for regional hub cities, ii) consensus building among those concerned, and iii) investor’s understanding, according to the concepts “Selection and Concentration” and “Respect for Local Intention”.

Recently, the investment climate has changed dramatically with the expansion of the Internet and the development of information communication technologies such as “Fin-Tech”. Information-intensive activities are very important to call for investment.

The “i-UR” is an information infrastructure for urban revitalization. It allows people to analyse and to visualize the situation and problems of urban areas according to the future vision of each area using geospatial information and virtual reality technologies. The quantitative analysis and visualization clearly show the cash-flow and spatial plan of the city and promotes understanding and encourages consensus building among relevant players, e.g. investors, citizens, and developers.

This document defines the encoding specification of the data for i-UR (which is called “i-UR Data”), and aims to assist the formation of social agreement and to improve the quality of urban investment in order to contribute to urban revitalization.
The i-UR Data is the combination of following data:

- a)	3-dimentional city objects and city model
- b)	Detailed information of city objects for analysis
- c)	Constraints/conditions (e.g. regulation) related to urban revitalization
- d)	Statistical grid data for global analysis and visualization 
- e)	Public transit information to consider urban function accumulation in regional planning

The i-UR Data Encoding Specification targets on b) to e) data, as a) is already defined in City Geography Markup Language (CityGML). CityGML is an XML/GML based 3D data standard developed by Open Geospatial Consortium (OGC) for the representation, storage and exchange of 3D city models and is widely used in the application fields related to urban areas.
The i-UR Data Encoding Specification is composed of four parts listed below. Each encoding specification is tied up with each component and is an extension of CityGML according to the rules of the Application Domain Extensions (ADE) to ensure data interoperability. Thus i-UR Data aims to be utilized in various application fields, such as disaster prevention, tourism and to carry out urban revitalization.
Part 1: Urban Object Data Encoding Specification
This document targets on b) Detailed information of city objects for analysis and defines them as properties of CityGML object.
Part 2: Urban Function Data Encoding Specification	
This document targets on c) Constraints/conditions related to urban revitalization and defines constraints and conditions as subclasses of the root class in CityGML.
Part 3: Statistical Grid Data Encoding Specification
This document targets on d) Statistical grid data for global analysis and visualization, and defines a statistical grid as subclasses of the root class in CityGML to describe rough city models with a unified unit among cities. 
Part 4: Public Transit Data Encoding Specification
This document targets on e) Public transit information to consider urban function accumulation in regional planning, and defines a public transit (e.g. bus route, train route) as subclasses of the root class in CityGML.

Furthermore, this document defines new Levels of Detail (LOD) for a broad description of city models. These extended LODs enable user to describe rough city models which do not have to be detailed but should be necessary regional or national planning. This ExtendedLOD concept is commonly applied to related modules, and the details of ExtendedLOD is described in Part 2 and Part 3 of this document where this concept is instantiated.
