![alt text](http://git.realestatecore.io/img/RealEstateCore_LOGO_cmyk_black_small.png)

# RealEstateCore - for and by property owners

Ever increasing amounts of data are generated by and within buildings. Several different systems exist to control climate, lighting, access control, etc., not to mention all the new data sources that emerge from IoT devices, all of which generate data. These large amounts of heterogeneous data need to be organized.
Please visit: https://www.realestatecore.io/

## What is the RealEstateCore?
RealEstateCore is a common language that will enable control over buildings and development of new services – the facilitator of the promises of a digital transformation. RealEstateCore is a domain ontology preparing buildings to interact with the Smart City.

RealEstateCore is not aiming to be a new standard, but we rather intend for it bridge existing standards and find the common denominators. RealEstateCore uses and maps such existing standards in a pragmatic manner by adding annotations (which can be reused by the community directly if needed).

## What are the benefits for the property owners?
Property owners can use RealEstateCore to describe the data of interaction within the buildings that they operate – as well as the management, storage, and sharing of this data. RealEstateCore is a modular ontology, that is, a collection of data schemas that describe concepts and relations that can occur in data that is generated to model buildings and building systems, or that is sourced from such systems. For instance, RealEstateCore covers building structures, ownership, inhabitants, technical systems and sensors, events, etc.

## Modules to make it customizable
RealEstateCore consists of a set of modules, which in the current version include:

* Metadata -- various annotation properties used to document the entire ontology suite.
* Core -- collects the top-level classes and properties that span over or are reused within multiple REC modules. Imports the Metadata module, and is imported by all other specific child modules.
* Building -- different types of building components and rooms.
* Device -- device types (sensors and actuators), device configuration, device actuation, etc.
* Agents -- different types of agents (persons, groups, organizations) and the relations they have.
* Lease -- contracts, leasable premises, types of premises, etc.

The purpose of using different modules to model domain-specific details is to facilitate customization for each user, e.g. a fictitious RetailPropertyOwner might use the Core and Device modules just as they are, but might want to modify the Building module to reflect the type of business that they do (e.g., by providing a more suitable taxonomy of room types for retail real estate).

The Core module is an upper ontology supporting the more specific modules that model domain specific details. This structure makes it easy to in the future add more domain ontologies to expand the usefulness of the RealEstateCore.

## Best practise
We have put together an example deployment version of RealEstateCore that imports all of the second-level REC modules (each of which import the shared Core module) into a ready-to-use “REC Full” ontology.
https://www.realestatecore.io/getting-started

## How to contribute?
The RealEstateCore consortium is working on improving the core ontology, adding more modules, and as well is working on making better tools to integrate and use the ontology in smart building platforms and its applications.

We encourage you to contribute to make RealEstateCore better. Please point out bugs or peculiarities, add or extend modules and vocabularies, suggest improvements in order to evolve the RealEstateCore.

* Comment or create a new Issue for bug reporting
* For improvements, please fork the rec repository, make your changes and send a pull request
